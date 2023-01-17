<template>
    <div>
        <form action="">
            <input type="text" name="nome" id="" placeholder="inserisci nome" v-model="user_data.name">
        </form>

        <form action="">
            <input type="text" name="nome" id="" placeholder="inserisci cognome" v-model="user_data.surname">
        </form>

        <form action="">
            <input type="email" name="" id="" placeholder="inserisci email" v-model="user_data.email">
        </form>

        <form action="">
            <input type="tel" name="" id="" placeholder="inserisci telefono" v-model="user_data.phone">
        </form>

        <form action="">
            <input type="file" name="" id="" placeholder="inserisci CV" v-on="user_data.cv">
        </form>

        <button type="submit" @click="sendMail">submit</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            user_data: [
                {
                    name: "",
                    surname: "",
                    email: "",
                    phone: "",
                    cv: "",
                    
                }
            ]
        }
    },
    methods: {
        sendMail() {
            this.$mail.send({
                from: 'c.termo@sincos.it',
                subject: 'Contact form message',
                text: 'prova',
                to: 'christiantermo84@gmail.com',
            })
        }
    }
}
</script>