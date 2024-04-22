<script>
export default {
    data() {
        return {
            otp: {
                otp1: "",
                otp2: "",
                otp3: "",
                otp4: ""
            }
        }
    },
    methods: {
        otpSubmit() {
            console.log("Otp has been submitted", this.otp)
            this.otp.otp1 = ""
            this.otp.otp2 = ""
            this.otp.otp3 = ""
            this.otp.otp4 = ""
        }
    }
}
</script>

<template>
    <div class="container">
        <div class="logo_heading">
            <img src="../assets/image.png" class="logo" alt="logo" />
            <h1>Streamed</h1>
        </div>
        <div class="headings_inputs">
            <div class="headings">
                <h1>Check your email for a code</h1>
                <p class="subheading">We've sent a 6-character code to john_brown@company.com
                    The code expires shortly, so please enter it soon..</p>
            </div>

            <div class="inputs">
                <input type="number" v-model="otp.otp1">
                <input type="number" v-model="otp.otp2">
                <input type="number" v-model="otp.otp3">
                <input type="number" v-model="otp.otp4">
            </div>


            <div class="submitButton">
                <button class="btn" @click="otpSubmit" >Continue</button>
            </div>

            <div class="signup">
                <p class="paraMargin">Didn't get SMS? <span class='greenText'>Send again </span></p>
                <p>Can't find code? Check your spam folder</p>
            </div>
        </div>
        <div class="footer">
            <p>By proceeding, you agree to the Terms of Service
                and <span class='greenText'>Privacy Policy</span></p>
        </div>
    </div>
</template>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #fff;
    width: 90vw;
    font: Poppins;
}

.logo_heading {
    display: flex;
    align-items: center;
    position: absolute;
    top: 30px;
}

.logo_heading h1 {
    font-size: 2rem;
    font-weight: 700;
    margin-left: 10px;

}

.logo {
    width: 36.32px;
    height: 58.12px;
    gap: 0px;
    opacity: 0px;

}

.subheading {
    width: 30vw;
}

.headings_inputs {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 40vw;
    margin-top: -20px;
}

.headings {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.headings h1 {
    font-size: 1.7rem;
    font-weight: 700;
    margin-left: 10px;
}

.subheading {
    font-size: 14px;
    font-weight: 400;
}

.paraMargin {
    margin-bottom: 20px;
    margin-top: 10px;
}


.inputs {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    gap: 10px;
    margin-top: 20px;
}

input {
    padding: 18px 16px;
    width: 5vw;
    border-radius: 8px;
    border: 1px solid #bac3bc80;
    font-size: 18px;
}

.btn {
    width: 25vw;
    height: 50px;
    padding: 14px 16px 14px 16px;
    border-radius: 8px;
    border: 1px solid #bac3bc80;
    opacity: 0px;
    background: #3CC553;
    color: #fff;
    font-size: 16px;
    margin-top: 15px;
    cursor: pointer;
}

.signup {
    width: 25vw;
    font-size: 12px;
    margin-top: 10px;
}

.footer {
    position: absolute;
    bottom: 15px;
    width: 30vw;
    font-size: 16px;
    font: poppins;
    text-align: center;
    font-weight: 700;
}

.greenText {
    color: #3CC553;
    ;
}

@media (min-width: 1024px) {}

@media only screen and (max-width: 768px) {
    .container {
        width: 90vw;
        margin-top: -15px;
    }

    .headings_inputs {
        width: 80vw;
    }

    .subheading {
        width: 80vw;
    }

    input {
        width: 15vw;
    }


    .btn {
        width: 80vw;
    }

    .signup {
        width: 80vw;
    }

    .footer {
        width: 80vw;
    }

}
</style>
