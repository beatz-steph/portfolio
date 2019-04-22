<template>
    <section class="sction container scrollspy" id="contact">
        <div class="row">
            <div class="col s12 l5">
                <h2 class="ingo-text text-darken-4"> Get in touch</h2>
                <p>In case you need for a job, you can  fill in the fields provided and i will send you a response as soon as possible
                </p>
                <p>
                    It is important to fill your personal details correctly
                </p>
            </div>
            <div class="col s12 l5 offset-l2">
                <form name="contact" method="POST" data-netlify="true" netlify>
                    <div class="input-field">
                        <i class="material-icons prefix">person</i>
                        <input type="text" id="name">
                        <label for="name">Enter your name</label>
                    </div>
                    <div class="input-field">
                        <i class="material-icons prefix">email</i>
                        <input type="email" id="email">
                        <label for="email">Your email</label>
                    </div>
                    <div class="input-field">
                        <i class="material-icons prefix">message</i>
                        <textarea id="message" class="materialize-textarea"></textarea>
                        <label for="message">
                            Your message
                        </label>
                    </div>
                    <div class="input-field">
                        <input type="text" id="date" class="datepicker">
                        <label for="date">Choose a date yoy need me for</label>
                    </div>
                    <div class="input-field">
                        <p>Services required...</p>
                        <p>
                            <label>
                                <input type="checkbox">
                                <span>UI/UX</span>
                            </label>
                        </p>
                        <p>
                            <label>
                                <input type="checkbox">
                                <span>Frontend</span>
                            </label>
                        </p>
                        <p>
                            <label>
                                <input type="checkbox">
                                <span>Backend</span>
                            </label>
                        </p>
                    </div>
                    <div class="input-field center">
                        <button class="btn">
                            <i class="material-icons right">send</i>
                            Submit</button>
                    </div>
                </form>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:'Form'
}
</script>

<style scoped>

</style>
