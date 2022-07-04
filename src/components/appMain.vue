<template>

    <main>

        <div class="input-box">
            <input type="text" placeholder="Add a new todo" />
            <button>+</button>
        </div>

    </main>

</template>

<script></script>

<style>

main{
    width: 100%;
    padding: 40px 50px;
    display: flex;
    justify-content: center;
}

main .input-box{
    max-width: 500px;
    width: 75%;
    position: relative;
}

main .input-box input{
    padding: 0px 60px 0px 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
    width: 100%;
    height: 38px;
    font-size: 1.1em;
}

main .input-box input:focus{
    outline: none;
}

main .input-box button{
    position: absolute;
    right: 0;
    background: rgb(22, 143, 22);
    color: #fff;
    width: 50px;
    height: 100%;
    border-radius: 0px 8px 8px 0px;
    border:none;
    outline: none;
    cursor: pointer;
    font-size: 1.6em;
    font-weight: 600;
}


</style>