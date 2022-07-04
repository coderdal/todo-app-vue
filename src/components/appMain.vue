<template>

    <main>

        <div class="input-box">
            <input type="text" placeholder="Add a new todo" />
            <button>+</button>
        </div>

        <div class="todo-list">

            <ul>

                <li>
                    Lorem ipsum dolor sit amet consectetur.
                    <span class="actions">
                        <button><svg version="1.1" fill="#41B883" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve"><polygon points="437.3,30 202.7,339.3 64,200.7 0,264.7 213.3,478 512,94 "/></svg></button>
                        <button><svg version="1.1" fill="#ff3c3c" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 1792 1792" style="enable-background:new 0 0 1792 1792;" xml:space="preserve"><path d="M1082.2,896.6l410.2-410c51.5-51.5,51.5-134.6,0-186.1s-134.6-51.5-186.1,0l-410.2,410L486,300.4c-51.5-51.5-134.6-51.5-186.1,0s-51.5,134.6,0,186.1l410.2,410l-410.2,410c-51.5,51.5-51.5,134.6,0,186.1c51.6,51.5,135,51.5,186.1,0l410.2-410l410.2,410c51.5,51.5,134.6,51.5,186.1,0c51.1-51.5,51.1-134.6-0.5-186.2L1082.2,896.6z"/></svg></button>
                    </span>
                </li>
                <li>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam, voluptatem?
                    <span class="actions">
                        <button><svg version="1.1" fill="#41B883" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve"><polygon points="437.3,30 202.7,339.3 64,200.7 0,264.7 213.3,478 512,94 "/></svg></button>
                        <button><svg version="1.1" fill="#ff3c3c" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 1792 1792" style="enable-background:new 0 0 1792 1792;" xml:space="preserve"><path d="M1082.2,896.6l410.2-410c51.5-51.5,51.5-134.6,0-186.1s-134.6-51.5-186.1,0l-410.2,410L486,300.4c-51.5-51.5-134.6-51.5-186.1,0s-51.5,134.6,0,186.1l410.2,410l-410.2,410c-51.5,51.5-51.5,134.6,0,186.1c51.6,51.5,135,51.5,186.1,0l410.2-410l410.2,410c51.5,51.5,134.6,51.5,186.1,0c51.1-51.5,51.1-134.6-0.5-186.2L1082.2,896.6z"/></svg></button>
                    </span>
                </li>

            </ul>

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
    align-items: center;
    flex-direction: column;
}

/* Input Box */

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


/* Todo List */

main .todo-list{
    padding: 100px 30px;
    max-width: 500px;
    width: 80%;
}

main .todo-list ul{
    list-style: none;
}

main .todo-list ul li{
    background: #fff;
    padding: 8px 60px 8px 15px;
    color: #212d38;
    border-radius: 8px;
    position: relative;
    margin: 4px 0px;
}

main .todo-list ul li .actions{
    position: absolute;
    right: 0;
    top: 0;
    height: 100%;
    width: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #d7dce0;
    padding: 0 10px;
    border-radius: 0px 8px 8px 0px;
}

main .todo-list ul li .actions button{
    background: transparent;
    cursor: pointer;
    border: none;
    margin-right: 5px;
}

main .todo-list ul li .actions button svg{
    width: 20px;
}



</style>