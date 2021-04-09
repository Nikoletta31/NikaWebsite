<template>
    <div class="project-body">
        <div class="project">
        <h1>Actioneo Vue.Js</h1>
        <p>The project was realized on VueJs framework using MongoDB as a database and Laravel as a back-end framework.</p>
        </div>
      
        <div class="container-project">
<img class="first" src="@/assets/actio.png" data-aos="zoom-in" data-aos-duration="1000"/>
<p>Lawyers' dashboard displaying the clients and the relations of the client. <br>
The client is able to have professional and personal relation. As well as the client can be corporate or physical.<br>
To realize this dashboard I was using Bootstrap and SASS for the design modifications.<br>
The data was connected with the help of API endpoints in Vuex.</p>
        </div>
                <div class="container-project1">
                    <p>The possibility of data modification was presented on all the sections of the page.<br>
                    With the help of CRUD method, our cutomer is able to delete, add or modify various data of their clients. 
                    All the data manipulations were saved on MongoDB.<br>
                    Additional features such as reearch of the client in the data and passing the relation of the client as a client was created as well.</p>
<img class="second" src="@/assets/form.png" data-aos="zoom-in" data-aos-duration="1000"/>

        </div>
            <Other/>
    </div>
</template>

<script>
import Other from "@/components/Other.vue";

export default {
    name:"Actioneo", 
    components: {Other},
    
}
</script>

<style lang="scss" scoped>

@import "@/assets/styles/project-about.scss";


</style>