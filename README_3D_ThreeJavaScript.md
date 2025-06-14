# 3D Horse Animation Scene

This project demonstrates a simple interactive 3D scene featuring a horse running along a track. Built with glTF models, Three.js, and basic interactivity controls, it serves as a lightweight prototype or base for more complex animations or simulations.

---

## 🚀 Features

- **Running Horse Animation**  
  The horse model runs forward along the Z-axis, giving a natural sense of motion.

- **Track with Grass**  
  A simple track is rendered with grass elements on both sides to enhance realism.

- **Dust Effects Under Hooves**  
  Four separate dust emitters are positioned under the horse’s legs to simulate realistic movement effects.

- **Click or Tap Interaction**  
  Clicking or tapping the scene toggles the horse's movement — it stops and resumes on subsequent input.

---

## 🔧 Technical Overview

### 🐎 Animated Horse Model
- A glTF model with prebuilt walking animation is loaded into the scene.
- Animation is controlled using Three.js’s `AnimationMixer`.

### 🎞️ AnimationMixer
- Used to play and manage the horse's walk cycle.
- Enables smooth, built-in animation without custom rigging.

### 🧭 OrbitControls
- Adds camera interactivity.
- Users can rotate, pan, and zoom to explore the scene.

### 💡 Lighting & Background
- Ambient and directional lights are added for clarity and visual appeal.
- The background is set to black to keep focus on the animated model.

---

## 📦 Dependencies

- [Three.js](https://threejs.org/)
- glTF Loader
- OrbitControls

---

## 📁 Folder Structure (Example)

/public
/models
horse.glb
/src
index.html
main.js
dust.js
controls.js

Links for me: 
https://marvned.github.io/3DThreeJS/3D2_Threejs_v.9Horse_v01.html
Explanation and Advantages of This Approach

Animated Horse Model
We load a set of glTF models with built-in animations.

AnimationMixer
Allows us to play the model’s embedded animation — in our case, the horse's walking cycle.

OrbitControls
Adds interactivity: users can rotate the camera, zoom in and out of the scene.

Simple Lighting and Background
To make the horse stand out visually, we enable ambient and directional lighting, and use a black background.

Translation: 
Пояснения и преимущества этого решения
Модель движущейся лошади
Мы загружаем набор glTF-моделей с готовыми анимациями

AnimationMixer
Позволяет проигрывать встроенную анимацию модели — в нашем случае походку лошади .

OrbitControls
Добавляют интерактивность: можешь вращать камеру, приближать и отдалять сцену.

Простое освещение и фон
Чтобы животное выглядело выразительно, мы включили ambient и directional свет, и чёрный фон.
_____________________________________________________________________________________________________

3D2_Threejs_v.9Horse_v02interactiveMouseClickReaction.html
Let's lay out the track along the Z-axis — so it looks like the horse is running forward.
Add grass along both sides of the track.
Generate dust only under the hooves — create four separate dust emitters, approximately aligned with the horse's leg positions.
Implement mouse click or touch input: the horse stops when clicked/tapped. On the next click/tap, it resumes running. Interactivity.

Translation:
Развернём трассу вдоль (по оси Z) — чтобы лошадь как будто бежала вперёд.
Добавим траву по бокам трассы.
Сделаем пыль только под копытами — создадим по 4 отдельных "источника" пыли, примерно там, где ноги лошади двигаются.
Сделаем реакцию на клик мыши, или касание пальцем: лошадь останавливается. При последующем клике лошадь бежит. Интерактивность. 
