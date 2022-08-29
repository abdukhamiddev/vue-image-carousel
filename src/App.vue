<script setup>
// import items from "@/data/items.json";
import items from "./data/images.json";
import Slider from "./components/index.vue";
</script>
  
  <template>
  <Slider :items="items" />
</template>