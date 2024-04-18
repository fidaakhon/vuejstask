<script setup>
</script>

<template>
    <div class="container">
        <div class="logo_heading">
            <img src="../assets/image.png" class="logo" alt="logo" />
            <h1>Streamed</h1>
        </div>
        <div class="headings_inputs">
            <div class="headings">
                <h1>Hi, Welcome Back to Streamed</h1>
                <p class="subheading">We suggest using the email address that you use at work.</p>
            </div>
            <div class="icons">
                <div class="googleIcon">
                    <img src="../assets/google.png" class="icon" alt="google" />
                    <p>Continue with google</p>
                </div>
                <div class="googleIcon">
                    <img src="../assets/apple.png" class="icon" alt="google" />
                    <p>Continue with Apple</p>
                </div>
            </div>

            <div class="partitionLines">
                <div class="line"></div>
                <p>OR</p>
                <div class="line"></div>
            </div>

            <div class="emailInput">
                <label for="emai">Your Email</label>
                <input type="email" placeholder="eg- jhon@email.com" />
            </div>

            <div class="submitButton">
                <button class="btn">Continue</button>
            </div>

            <div class="signup">
                <p class=''>We,ll email you a magic code for password-free sign-in. Or you can <span
                        class='greenText'>sign in manually instead </span></p>
            </div>
        </div>
        <div class="footer">
            <p class=''>By proceeding, you agree to the Terms of Service
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

.headings_inputs {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 40vw;
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

.googleIcon {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 25vw;
    height: 45px;
    padding: 14px 16px 14px 16px;
    gap: 12px;
    border-radius: 8px;
    border: 1px solid #bac3bc80;
    cursor: pointer;
}

.icon {
    width: 20px;
    height: 20px;
}

.icons {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
    margin-top: 20px;
}

.partitionLines {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    margin-top: 20px;
}

.line {
    width: 12vw;
    height: 1px;
    background-color: #bac3bc80;
}

.emailInput {
    display: flex;
    flex-direction: column;
}

input {
    padding: 14px 16px;
    width: 25vw;
    border-radius: 8px;
    border: 1px solid #bac3bc80;
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

    .googleIcon {
        width: 80vw;
    }

    .icon {
        width: 20px;
        height: 20px;
    }

    .partitionLines {
        gap: 5px;
    }

    .line {
        width: 30vw;
    }

    .emailInput {
        width: 80vw;
    }

    input {
        width: 80vw;
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
