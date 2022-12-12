# jenhui

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style type="text/css">
        body {
            padding: 1rem;
        }
    </style>
</head>
<body>
    <div id="app">
        <input v-model="message" placeholder="edit me">
        <p>Message is: {{ message }}</p>
    </div>
    
    <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
    <script src="https://unpkg.com/vue@next"></script>

    <!-- <script type="text/javascript" src="js/jquery.min.js"></script> -->
    <script type="text/javascript">
        const vm = Vue.createApp({
            data () {
                return{
                    message: 'Hello'
                } 
            }
        });
        vm.mount('#app');
    </script>


</body>
</html>
