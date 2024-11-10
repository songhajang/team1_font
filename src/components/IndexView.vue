<template>
    <a href="./main.html" class="logo">Project Team 1</a>

    <div class="middle-img">
        <img src="../assets/headphone.png" alt="헤드폰 이미지">
    </div>

    <div class="left-word focus-in-expand-fwd">
        <p>Want a</p>
        <p class="bold">PLAYLIST?</p>
        <button class="login">
            <a href="#">LOGIN</a>
        </button>
        <button class="signUp">
            <a href="#">SIGN UP</a>
        </button>
    </div>

    <!-- Overlay와 모달 박스 추가 -->
    <div class="overlay"></div>
    <div class="modal-box tracking-in-expand-fwd" id="login-modal">
        <p>LOGIN</p>
        <input type="text" placeholder="ID" id="input-id">
        <br>
        <input type="password" placeholder="PW" id="input-pw">
        <br>
        <button class="close-modal">로그인 하기</button>
    </div>

    <div class="modal-box tracking-in-expand-fwd" id="signup-modal">
        <p>Sign up</p>
        <input type="text" placeholder="Name" id="signup-name">
        <input type="text" placeholder="ID" id="signup-id">
        <input type="password" placeholder="PW" id="signup-pw">
        <button class="close-modal">회원가입 하기</button>
    </div>
</template>

<script setup>
// TODO: vue 에서  @click 이벤트 찾아보기
// TODO: 반응형 변수(reative , ref) 찾아서 만들어 쓰면 코드 클린해짐 ~ 

// document.querySelector('.login').addEventListener('click', function () {
//     document.querySelector('.overlay').classList.add('active');
//     document.querySelector('#login-modal').classList.add('active', 'tracking-in-expand-fwd');
// });

// document.querySelector('.signUp').addEventListener('click', function () {
//     document.querySelector('.overlay').classList.add('active');
//     document.querySelector('#signup-modal').classList.add('active', 'tracking-in-expand-fwd');
// });

// document.querySelector('.overlay').addEventListener('click', function () {
//     document.querySelector('.overlay').classList.remove('active');
//     document.querySelectorAll('.modal-box').forEach(function (modal) {
//         modal.classList.remove('active', 'tracking-in-expand-fwd');
//     });
// });

// document.querySelectorAll('.close-modal').forEach(function (button) {
//     button.addEventListener('click', function () {
//         document.querySelector('.overlay').classList.remove('active');
//         document.querySelectorAll('.modal-box').forEach(function (modal) {
//             modal.classList.remove('active', 'tracking-in-expand-fwd');
//         });
//     });
// });
</script>
