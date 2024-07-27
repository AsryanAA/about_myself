<script setup>
</script>

<template>
    <header>
        <div class='first_block'>
            <img src='/favicon.ico' alt='logo' width='40px' height='40px'>
            <div>
                <h2>About myself</h2>
                <p>Welcome to my world</p>
            </div>
        </div>

        <ul class='second_block'>
            <li>
                <img class='icon' src='/profile.svg' alt='profile'>
                <b>Профиль</b>
            </li>
            <li>
                <img class='icon' src='/resume.svg' alt='resume'>
                <b>Резюме</b>
            </li>
            <li>
                <img class='icon' src='/poetry.svg' alt='poetry'>
                <b>Стихи</b>
            </li>
            <li>
                <img class='icon' src='/films.svg' alt='films'>
                <b>Фильмы</b>
            </li>
            <li>
                <img class='icon' src='/books.svg' alt='books'>
                <b>Книги</b>
            </li>
        </ul>
    </header>
</template>

<style scoped>
    header {
        display: flex;
        justify-content: space-between;
        border-bottom: 1px solid;
        padding: 10px 32px 10px 32px;
        border-color: rgb(203 213 255);
    }

    .icon {
        width: 22px;
        height: 22px;
    }

    .first_block {
        display: flex;
        align-items: center;
        gap: 16px;
    }

    .second_block {
        display: flex;
        align-items: center;
        gap: 12px;
    }

    li {
        display: flex;
        align-items: center;
        gap: 8px;
        cursor: pointer;
        color: rgb(195 195 195);
    }

    li:hover {
        color: black;
    }

    h2 {
        font-size: 20px;
        line-height: 28px;
        font-weight: 700;
        text-transform: uppercase;
    }
</style>