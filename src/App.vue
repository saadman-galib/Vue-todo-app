<template>
    <div class="app-container">
        <h1 class="app-title">Vuejs todos</h1>

        <div class="composer">
            <input
                type="text"
                placeholder="Type and hit enter..."
                class="composer__input"
            />
            <div class="filter">
                <div class="filter__left">
                    <button class="filter__button filter__button--active">
                        All (0)
                    </button>
                    <button class="filter__button">Pending (0)</button>
                    <button class="filter__button">Done (0)</button>
                </div>
                <div>
                    <button class="filter__button filter__button--danger">
                        Clear
                    </button>
                </div>
            </div>
        </div>

        <div class="todos">
            <!-- Todo start -->
            <div class="todo">
                <div class="todo__status-dot"></div>
                <div>
                    <p class="todo__content">sdfsa</p>
                    <small class="todo__time">
                        Wed Feb 09 2022 21:19:25 GMT+0600 (Bangladesh Standard
                        Time)
                    </small>
                </div>
            </div>
            <!-- Todo end -->

            <!-- Todo start -->
            <div class="todo">
                <div class="todo__status-dot"></div>
                <div>
                    <p class="todo__content">sdfsa</p>
                    <small class="todo__time">
                        Wed Feb 09 2022 21:19:25 GMT+0600 (Bangladesh Standard
                        Time)
                    </small>
                </div>
            </div>
            <!-- Todo end -->

            <!-- Todo start -->
            <div class="todo todo--done">
                <div class="todo__status-dot"></div>
                <div>
                    <p class="todo__content">sdfsa</p>
                    <small class="todo__time">
                        Wed Feb 09 2022 21:19:25 GMT+0600 (Bangladesh Standard
                        Time)
                    </small>
                </div>
            </div>
            <!-- Todo end -->
        </div>
    </div>
</template>

<script>
import "./assets/tailwind.css";

export default {
    name: "TodoApp",
    date() {
        return {
          
        };
    },
};
</script>
