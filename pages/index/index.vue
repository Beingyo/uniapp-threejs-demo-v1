<template>
	<view class="list-container">
	    <button type="primary" size="default" plain="true" @click="tap" id="cube">
	        cube
	    </button>
	    <button type="primary" size="default" plain="true" @click="tap" id="cubes">
	        cubes
	    </button>
	    <button type="primary" size="default" plain="true" @click="tap" id="cubeControls">
	        cubeControls
	    </button>
		<button type="primary" size="default" plain="true" @click="tap" id="glbModel">
		    glbModel
		</button>
		<button type="primary" size="default" plain="true" @click="tap" id="stlModel">
		    stlModel
		</button>
		<button type="primary" size="default" plain="true" @click="tap" id="objModel">
		    objModel
		</button>
		<button type="primary" size="default" plain="true" @click="tap" id="twoControls">
		    twoControls
		</button>
	    <button type="primary" size="default" plain="true" @click="tap" id="shadow">
	        shadow
	    </button>
		<button type="primary" size="default" plain="true" @click="tap" id="line">
		    line
		</button>
		<button type="primary" size="default" plain="true" @click="tap" id="uv">
		    uv
		</button>
		<button type="primary" size="default" plain="true" @click="tap" id="fold">
		    fold
		</button>
		<button type="primary" size="default" plain="true" @click="tap" id="play">
		    play
		</button>
	</view>
</template>

<script>
	export default {
		onLoad: function() {
			
		},
		methods: {
			tap(e) {
				uni.navigateTo({
				    url: '/pages/' + e.currentTarget.id + '/index'
				});
			}
		},
	}
</script>

<style>
	/* .list-container {
	  display: flex;
	  flex-direction: column;
	  justify-content: flex-start;
	  align-items: center;
	} */
	button {margin: 10px;}
</style>
