<template>
    <div>
        <Navbar />

        <section class="Abilities">

            <h1 class="heading"> MY <span>ABILITIES</span> </h1>

            <div class="row">

                <div class="info-container">

                    <h1>personal info</h1>

                    <div class="box-container">

                        <div class="box">
                            <h3> <span>name : </span> Chinnapat Khemthong </h3>
                            <h3> <span>age : </span> 19 </h3>
                            <h3> <span>email : </span> Chinnapat.khem@bumail.net </h3>
                            <h3> <span>address : </span> Nontaburi, Thailand 11140 </h3>
                        </div>

                        <div class="box">
                            
                            <h3> <span>Skill : </span> Can do everything </h3>
                            <h3> <span>Experience : </span> 1 week </h3>
                            <h3> <span>Language : </span> Thai , English , Vietnamese , Chinese , Filipino , Russian </h3>
                        </div>

                    </div>

                    

                </div>

                <div class="count-container">

                    <div class="box">
                        <h3>1 Day+</h3>
                        <p>Experience</p>
                    </div>

                    <div class="box">
                        <h3>1+</h3>
                        <p>Happy Clients</p>
                    </div>

                    <div class="box">
                        <h3>1+</h3>
                        <p>Project Completed</p>
                    </div>

                    <div class="box">
                        <h3>1+</h3>
                        <p>Certificates</p>
                    </div>

                </div>

            </div>

        </section>

        <!-- about section ends -->

        <!-- skills section starts  -->

        <section class="skills">

            <h1 class="heading"> <span>My</span> Skills </h1>

            <div class="box-container">
                <div class="box">
                    <img src="images/icon-1.png">
                    <h3>STEAM</h3>
                </div>
                <div class="box">
                    <img src="images/icon-2.png">
                    <h3>ORIGIN</h3>
                </div>
                <div class="box">
                    <img src="images/icon-3.png">
                    <h3>Battle.net</h3>
                </div>
                <div class="box">
                    <img src="images/icon-4.png">
                    <h3>Ubisoft</h3>
                </div>
                <div class="box">
                    <img src="images/icon-5.png">
                    <h3>Playstation</h3>
                </div>
                <div class="box">
                    <img src="images/icon-6.png">
                    <h3>Nintendo</h3>
                </div>
            </div>

        </section>

        <!-- skills section ends -->

        <!-- education section starts  -->

    </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
export default {
    components: { Navbar }
}
</script>

<style>
</style>