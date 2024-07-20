<script>
import { ref } from 'vue'
import Card from '../shared/components/Card.vue'
import Footer from '../shared/components/Footer.vue';

export default {
    name: 'Landing',
    components: {
        Card,
        Footer
    }
}
</script>

<template>
    <div>
        <header>
            <!-- Animaiton with Developer ... Front-End Developer -->
            <h1>Cristopher Eduardo Ascencio Cruz</h1>
        </header>

        <!-- First Section  -->
        <Card> 
            <h2>Professional Experience</h2>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel accusamus unde ducimus? Veniam dolorem earum minima dolor incidunt ad quos corrupti quasi unde et, recusandae delectus voluptas tempora eius explicabo.
            </p>
        </Card>

        <Card>
            <h2>Skills</h2>

            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eveniet corrupti temporibus iure maiores aliquid aut perspiciatis suscipit illo nihil repudiandae cum labore eum vel similique molestiae tenetur, in maxime iste.
            </p>
        </Card>

        <Card>
            <h2>Projects Portfolio</h2>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum vel libero, ad deserunt minima accusamus quos eum, voluptatibus praesentium sed suscipit quia voluptates quidem odit, voluptatem non. Ab, nesciunt dolor?
            </p>
        </Card>

        <Card>
            <h2>Education</h2>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum vel libero, ad deserunt minima accusamus quos eum, voluptatibus praesentium sed suscipit quia voluptates quidem odit, voluptatem non. Ab, nesciunt dolor?
            </p>
        </Card>

        <Card>
            <h2>Contact Me</h2>

            <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Suscipit itaque nesciunt enim libero rem recusandae omnis expedita nihil, cum aperiam repellat corrupti eaque unde, accusantium nam et ipsum perspiciatis. Pariatur?
            </p>
        </Card>

        <Footer>
            <p style="text-align: center;">© 2024 Software Developer Since 2021. All Rights Reserved</p>
        </Footer>
    </div>
</template>

<style>
    h1, h2, h3 {
        color: #333;
        text-align: center;
    }

    .contact-info {
        margin-top: 20px
    }
</style>