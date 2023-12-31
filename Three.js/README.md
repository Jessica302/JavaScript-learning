# Three.js
提供相機控制、照明、材質、幾何形狀的建立、動畫和物體交互等，讓使用者有豐富的3D體驗。
<br>
<br>
### Project-ATOM
<img src="https://github.com/Jessica302/JavaScript-learning/blob/main/Three.js/Atom.png" width=300>

使用Three.js創建原子核自轉和電子環繞的3D場景，包含場景設置、物體的創建和管理、照明效果的添加，並呈現動畫。其中運用到：
1. 創建scene和WebGL的renderer，將渲染器的畫布添加到網頁中。<br>
2. 設置camera的視角和位置。<br>
3. 使用THREE.Object3D創建物件群組，將電子和原子核添加到該群組中。通過generateBall創建球體，並設置不同的位置和顏色。<br>
4. 添加環境光AmbientLight和平行光DirectionalLight，提供場景的照明效果。<br>
5. 使用物件來模擬三顆環繞原子核運動的電子。每顆電子都具有運動半徑、運動速度和角度等屬性。<br>
6. 使用OrbitControls模組用滑鼠拖曳來控制攝影機的旋轉和縮放，以便觀察場景的不同角度。<br>
7. 監聽視窗大小變化事件，並在視窗大小變化時更新相機的投影矩陣和渲染器的大小，以確保場景在不同大小的螢幕上正確顯示。

