 <template>
     <li>
		<h2><a v-bind:href="artist.url" target="_blank">{{artist.name}}</a></h2>
		 <img :src="artist.image[2]['#text']"></img>   
     </li>
</template>
<script>
export default {
	name: 'artist',
	props: ['artist']
}
</script>