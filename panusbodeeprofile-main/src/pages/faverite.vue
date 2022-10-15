<template>
    <div>
        <Navbar />
        <section class="faverite">
            <h1 class="heading"> <span>my</span> Faverite </h1>
            <h3>Faverite I like </h3>
            <p>I like serie in Netflix and like example from Netflix Thailand  </p>
            <div class="box-container">
                <center><iframe width="1280" height="720" src="https://www.youtube.com/embed/7JD2ASO-T7w" title="เดี่ยว 13 Highlight - มุกเด็ด! เมื่อพี่ ‘โน้ต-อุดม’ พูดถึงงานศพและท่ามินิฮาร์ท 😂 | Netflix" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar }
}
</script>

<style>

</style>