## Virtual-Reality-CS5331- Project-1

# Introduction

My project is a recreation of my room and a room that depicts the current circumstances arounf the world. 

# Motivation
The idea of the project was to focus on the environments around us which had changed due to the Covid-19. For my project, I wanted to show how maasks and sanitizers have become a coomon affair. 

# Description
- The project was made using HTML and Aframe. Some pictures were uploaded on glitch and imported in the project using cdn. 

# The Room

I created the room using the following code: 

<!-- Ceiling -->
		    <a-plane position="0 10 0" rotation="90 0 0" width="50" height="50" shadow="" material="side:double; repeat: 10 10" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2FBrick-wallaper-For-Background-21.jpg?v=1602659682624"></a-plane>


		    <!-- Floor -->
		    <a-plane position="0 0 0" rotation="-90 0 0" width="50" height="50" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2F0cfdd85012f7ced746da13b4632d3852.jpg?v=1602659386125" material="side:double; repeat: 10 15"></a-plane>


    
		    <!-- Walls -->
		    <a-plane position="2.049 5 -25" width="40" height="10" scale="1.150 1.000 1.000" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2Fwall_texture_bricks_light_119816_1920x1080.jpg?v=1601763538247" material="side:double"></a-plane>
		    <a-plane position="0 5 25" width="50" height="10" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2Fwall_texture_bricks_light_119816_1920x1080.jpg?v=1601763538247" material="side:double;  repeat: 3 1"></a-plane>
		    <a-plane position="-25 5 0" rotation="0 90 0" width="50" height="10" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2Fwall_texture_bricks_light_119816_1920x1080.jpg?v=1601763538247" material="side:double"></a-plane>
		    <a-plane position="25 5 0" rotation="0 90 0" width="50" height="10" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2Fwall_texture_bricks_light_119816_1920x1080.jpg?v=1601763538247" material="side:double"></a-plane>
      		    <a-plane position="7.024 5.262 -7.683" rotation="0 90 0" width="50" height="10" scale="0.700 1.000 1.000" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2Fwall_texture_bricks_light_119816_1920x1080.jpg?v=1601763538247" material="side:double"></a-plane>
	
	
The ceilings were created using the following:
		    
		    <!-- Ceiling -->
		    <a-plane position="0 10 0" rotation="90 0 0" width="50" height="50" shadow="" material="side:double; repeat: 10 10" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2FBrick-wallaper-For-Background-21.jpg?v=1602659682624"></a-plane>
		    
The floor was created using the code below:

<!-- Floor -->
		    <a-plane position="0 0 0" rotation="-90 0 0" width="50" height="50" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2F0cfdd85012f7ced746da13b4632d3852.jpg?v=1602659386125" material="side:double; repeat: 10 15"></a-plane>
      
Since the room is divided into two parts, I had to create five walls for the same:

 <!-- Walls -->
		    <a-plane position="2.049 5 -25" width="40" height="10" scale="1.150 1.000 1.000" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2Fwall_texture_bricks_light_119816_1920x1080.jpg?v=1601763538247" material="side:double"></a-plane>
		    <a-plane position="0 5 25" width="50" height="10" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2Fwall_texture_bricks_light_119816_1920x1080.jpg?v=1601763538247" material="side:double;  repeat: 3 1"></a-plane>
		    <a-plane position="-25 5 0" rotation="0 90 0" width="50" height="10" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2Fwall_texture_bricks_light_119816_1920x1080.jpg?v=1601763538247" material="side:double"></a-plane>
		    <a-plane position="25 5 0" rotation="0 90 0" width="50" height="10" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2Fwall_texture_bricks_light_119816_1920x1080.jpg?v=1601763538247" material="side:double"></a-plane>
      		    <a-plane position="7.024 5.262 -7.683" rotation="0 90 0" width="50" height="10" scale="0.700 1.000 1.000" src="https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2Fwall_texture_bricks_light_119816_1920x1080.jpg?v=1601763538247" material="side:double"></a-plane>
	
              
After building the room, I created the environment outisde using assets that I downloaded from SketchFab. 

The room is divided into Covid and Non Covid Mode. 

![Image](https://codesbya.github.io/CS5331-Project-1/Covid Mode.png)

![Image](https://codesbya.github.io/CS5331-Project-1/Noncovid.png)

To add components to the room, I imported a few models from SketchFab. The following code displays all the models that were imported:

 
  
      	
	            	<a-asset-item id="human" src="assets/human/scene.gltf"> </a-asset-item>
            		<a-asset-item id="scene" src="assets/scene/scene.gltf"> </a-asset-item>
            		<a-asset-item id="screen" src="assets/screen/scene.gltf"> </a-asset-item>
             		<a-asset-item id="table" src="assets/table/scene.gltf"> </a-asset-item>
                	<a-asset-item id="computer" src="assets/computer/scene.gltf"> </a-asset-item>
                	<a-asset-item id="fridge" src="assets/fridge/scene.gltf"> </a-asset-item>
              		<a-asset-item id="floor" src="assets/floor/scene.gltf"> </a-asset-item>
            		<a-asset-item id="door" src="assets/door/scene.gltf"> </a-asset-item>
            		<a-asset-item id="farmer" src="assets/farmer/scene.gltf"> </a-asset-item>
            		<a-asset-item id="bed" src="assets/bed/scene.gltf"> </a-asset-item>
            		<a-asset-item id="couch" src="assets/couch/scene.gltf"> </a-asset-item>
            		<a-asset-item id="asset" src="assets/asset/scene.gltf"> </a-asset-item>
            		<a-asset-item id="car" src="assets/car/scene.gltf"> </a-asset-item>
            		<a-asset-item id="chair" src="assets/chair/scene.gltf"> </a-asset-item>
            		<a-asset-item id="corona" src="assets/corona/scene.gltf"> </a-asset-item>
            		<a-asset-item id="mask" src="assets/mask/scene.gltf"> </a-asset-item>
            		<a-asset-item id="rug" src="assets/rug/scene.gltf"> </a-asset-item>
            		<a-asset-item id="shelf" src="assets/shelf/scene.gltf"> </a-asset-item>
            		<a-asset-item id="sofa" src="assets/sofa/scene.gltf"> </a-asset-item>
            		<a-asset-item id="patio" src="assets/sofa/scene.gltf"> </a-asset-item>
            		<a-asset-item id="mask2" src="assets/mask2/scene.gltf"> </a-asset-item>
            		<a-asset-item id="mask1" src="assets/mask1/scene.gltf"> </a-asset-item>
            		<a-asset-item id="mask3" src="assets/mask3/scene.gltf"> </a-asset-item>
            		<a-asset-item id="table1" src="assets/table1/scene.gltf"> </a-asset-item>
            		<a-asset-item id="speaker" src="assets/speaker/scene.gltf"> </a-asset-item>
                    <a-asset-item id="drm" src="assets/drm/scene.gltf"> </a-asset-item>
            		<a-asset-item id="drd" src="assets/drd/scene.gltf"> </a-asset-item>
            		<a-asset-item id="san" src="assets/san/scene.gltf"> </a-asset-item>
            		<a-asset-item id="grass" src="assets/grass/scene.gltf"> </a-asset-item>
                    <a-asset-item id="CeilingfanO" src="https://cdn.glitch.com/1eae885f-ae53-4ff4-8f1d-24b94e81e988%2F74e63c0c-df5a-4f88-a0dc-e7118cf071c5_540%20Ceiling%20Fan.obj?v=1600892230889"> </a-asset-item>
                    <a-asset-item id="CeilingfanM" src="https://cdn.glitch.com/1eae885f-ae53-4ff4-8f1d-24b94e81e988%2F74e63c0c-df5a-4f88-a0dc-e7118cf071c5_540%20Ceiling%20Fan.mtl?v=1600892224519"></a-asset-item> 
        


    </a-assets>


                    
    
            <!--       <a-entity id="1" gltf-model="#human"  position="22.480 -0.435 17.350" scale="1 0.800 0.650" height="0.10" geometry="primitive: plane; width: 22; height:4"> </a-entity> -->
                   <a-entity id="2" gltf-model="#screen"  position="-0.55 2.338 -14.63" scale="5 4 4" height="0.10" geometry="primitive: plane; width: 22; height:4"> </a-entity>
                   <a-entity id="3" gltf-model="#table"  position="10.263 0.112 -4.679" scale="4 3 3" height="0.10" geometry="primitive: plane; width: 22; height:4"> </a-entity>
                   <a-text value="Hover over the speakers to play music" position="16.248 4.290 -2.072" scale=" 1.5 2 1"></a-text>
                   <a-entity id="4" gltf-model="#computer"  rotation="0 90 0" position="-17.73 1.856 10.50" scale="1 0.6 1" height="0.10" geometry="primitive: plane; width: 22; height:4"> </a-entity>
                   <a-entity id="5" gltf-model="#fridge" rotation="0 90 0"  position="22.137 0.148 22.030" scale="1.5 1.8 1.5" height="0.10" geometry="primitive: plane; width: 22; height:4"> </a-entity>
                   <a-entity id="6" gltf-model="#door" rotation="0 0 0"  position="-20.556 -0.014 -24.765 " scale="5.100 5.100 4.8"  geometry="primitive: plane; width: 1; height:2"> </a-entity>
               <!--        <a-entity id="a" gltf-model="#farmer"  position="22.391 0.199 11.198" scale="1 1.1 0.8" height="0.10" geometry="primitive: plane; width: 22; height:4"> </a-entity> -->
                   <a-entity id="b" gltf-model="#bed"  position="-0.395 0.024 18.498"  scale="0.400 0.200 0.400" rotation="0 180 0" > </a-entity>
                   <a-entity id="c" gltf-model="#couch"  position="-20.895 2.940 -3.212"  scale="2.000 1.500 1.300" rotation="0 90.000 0" > </a-entity>
                   <a-entity id="d" gltf-model="#asset"  position="-27.883 0.373 -3.212"  scale="1 1 1" rotation="0 90.000 0" > </a-entity>
                   <a-entity id="e" gltf-model="#car"  position="-69.602 2.940 -3.212"  scale="0.010 0.010 0.010" rotation="0 90.000 0" > </a-entity>
                   <a-entity id="f" gltf-model="#chair"  position="-16.506 0.030 11.681"  scale="0.003 0.003 0.003" rotation="0 -90.000 0" > </a-entity>
                   <a-entity id="g" gltf-model="#corona"  position="11.032 2.940 -3.212"  scale="0.005 0.005 0.005" rotation="0 90.000 0" material="opacity: 0" class="intersectable" >
<a-animation begin="click" attribute="position" from= "11.032 2.940 -3.212 "to=  "14.729 2.930 -6.259"dur="30000" direction="alternate" easing="ease-in-out" ></a-animation>   </a-entity>
                   <a-entity id="g" gltf-model="#corona"  position="14.729 2.930 -6.259"  scale="0.005 0.005 0.005" rotation="0 90.000 0" material="opacity: 0" class="intersectable" >
<a-animation begin="click" attribute="position" from= "22.480-0.008 17.350 "to=  "11.032 2.940 -3.212"dur="30000" direction="alternate" easing="ease-in-out" ></a-animation>   </a-entity>
                   <a-entity id="h" gltf-model="#mask"  position="9.123 1.695 -4.753"  scale="0.500 0.500 0.500" rotation="50 90.000 0" material="opacity: 0"> </a-entity>
                   <a-entity id="i" gltf-model="#rug"  position="-0.762 -0.156 -2.293"  scale="0.100 0.100 0.100" rotation="0 90.000 0" > </a-entity>
                   <a-entity id="j" gltf-model="#shelf"  position="23.915 0.132 -23.397"  scale="0.020 0.055 0.050" rotation="0 -90.000 0" > </a-entity>
                   <a-entity id="k" gltf-model="#shelf"  position="23.915 0.092 -20.204"  scale="0.020 0.055 0.050" rotation="0 -90.000 0" > </a-entity>
                   <a-entity id="l" gltf-model="#patio"  position="15.596 0.060 -22.338"  scale="0.020 0.030 0.050" rotation="0 0 0" > </a-entity>
                   <a-entity id="m" gltf-model="#mask2"  position="10.477 1.433 -4.723"  scale="1 1 1" rotation="0 0 0" material="opacity: 0"> </a-entity>
                   <a-entity id="n" gltf-model="#mask3"  position="21.866 -3.247 -3.891"  scale="0.020 0.030 0.050" rotation="0 0 0" material="opacity: 0"> </a-entity>
                   <a-entity id="o" gltf-model="#table1"  position="22.121 1.056 -3.216"  scale="7.000 2.000 2.000" rotation="0 90 0" > </a-entity>
                   <a-entity id="p" gltf-model="#speaker"  position="22.360 1.659 -2.711"  scale="1 1 1" rotation="0 0 0" > </a-entity>
                   <a-entity id="q" gltf-model="#grass"  position="-0.762 -0.156 -2.293"  scale="0.100 0.100 0.100" rotation="0 0 0" > </a-entity>
                   <a-entity id="r" gltf-model="#san"  position="22.220 2.093 -2.862"  scale="0.250 0.400 0.200" rotation="0 0 0" material="opacity: 0"> </a-entity>
                   <a-entity id="r" gltf-model="#san"  position="8.229  1.774 -4.592"  scale="0.250 0.400 0.200" rotation="0 0 0" material="opacity: 0" > </a-entity>
                   <a-entity id="r" gltf-model="#drm"  position="13.272 0.040 14.386"  scale="0.250 0.350 0.350" rotation="0 180.000 0" material="opacity: 0" > </a-entity>
                   <a-entity id="r" gltf-model="#drd"  position="17.754 0.020 20.242"  scale="0.040 0.035 0.035" rotation="0 180 0" material="opacity: 0"> </a-entity>


# The objects that can be interacted in the room are:

- The Speakers
- The two entities that move at a 6 feet distance. 

# Dynamic object used: 

The fan in the non covid room. 

![Image](https://codesbya.github.io/CS5331-Project-1/Outside.png)

The images displayed in the non covide room were taken by me and precisely replicate the wall in my room. the frame around the images was also created by me using aframe. 

The code used for the images is as follows:

 <a-entity id="p1" position="1.132 4.711 -24.966" rotation="0 0 0" scale="4.000 3.000 1" geometry="primitive: plane; width:2; height:2"
                  material="src:https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2FIMG_6735.JPG?v=1602698681560; repeat: 1 1"></a-entity>
       <a-entity id="p1" position="-7.496 4.711 -24.966" rotation="0 0 0" scale="4.000 3.000 1" geometry="primitive: plane; width:2; height:2"
                  material="src:https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2FIMG_6026.JPG?v=1602698678718; repeat: 1 1"></a-entity>
        <a-entity id="p1" position="-15.771 4.711 -24.966" rotation="0 0 0" scale="4.000 3.000 1" geometry="primitive: plane; width:2; height:2"
                  material="src:https://cdn.glitch.com/3b4c7cde-0c5f-4bbb-b553-305f2019aacb%2FIMG_6527.JPG?v=1602698675351; repeat: 1 1"></a-entity>
		  
		  
The frame was created using the following code:
		  
		  
      <!-- Frame -->
      
      <a-box id="x" scale="0.100 0.100 25.000" position="-7.325 1.696 -24.960" color="white" rotation="0 90.000 0"></a-box>
            <a-box id="x" scale="0.100 0.100 25.000" position="-7.325 7.809 -24.960" color="white" rotation="0 90.000 0"></a-box>
                  <a-box id="x" scale="0.100 0.100 6.000" position="-19.857 4.745 -24.960" color="white" rotation="90 90.000 0"></a-box>
                  <a-box id="x" scale="0.100 0.100 6.000" position="5.230 4.745 -24.960" color="white" rotation="90 90.000 0"></a-box>

# Conclusion 
As someone who has never created a VR project before, this subject and topic has definetly helped me understand the concept. Since the project was so interesting, it has definetly helped us in thinking and showcasing it differently. 
