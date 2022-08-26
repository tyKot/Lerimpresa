<template>
    <main>
        <div class="player__main">
            <div class="player">
                <div class="player-bg">
                    <img class="main_player" src="../assets/player_circle.png" alt="player">

                    <div class="player__info">
                        <h3 class="player_name-track">If the last star fell, a new star would rise</h3>
                        <span class="track-time">0:00</span>
                        <div class="player__controls">
                            <div class="previous">
                                <img src="../assets/skip-back.svg" alt="">
                            </div>
                            <div class="pause">
                                <img src="../assets/play.svg" alt="">
                            </div>
                            <div class="next">
                                <img src="../assets/skip-forward.svg" alt="">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="player__menu">
                <div class="genre-music">
                    <div class="genre-music__items">
                        <a href="#" @click="activeGenre = 1" :class="{ active: activeGenre == 1 }"
                            class="genre-music__item">all tracks</a>
                        <a href="#" @click="activeGenre = 2" :class="{ active: activeGenre == 2 }"
                            class="genre-music__item">rock</a>
                        <a href="#" @click="activeGenre = 3" :class="{ active: activeGenre == 3 }"
                            class="genre-music__item">acoustic</a>
                        <a href="#" @click="activeGenre = 4" :class="{ active: activeGenre == 4 }"
                            class="genre-music__item">instrumental</a>
                    </div>
                    <hr>
                    <div class="album-list">
                        <div class="album-list__items">
                            <a href="#" @click="activeAlbum = 1" :class="{ active: activeAlbum == 1 }"
                                class="album-list__item">all</a>
                            <a href="#" @click="activeAlbum = 2" :class="{ active: activeAlbum == 2 }"
                                class="album-list__item">album1</a>
                            <a href="#" @click="activeAlbum = 3" :class="{ active: activeAlbum == 3 }"
                                class="album-list__item">album2</a>
                            <a href="#" @click="activeAlbum = 4" :class="{ active: activeAlbum == 4 }"
                                class="album-list__item">album3</a>
                            <a href="#" @click="activeAlbum = 5" :class="{ active: activeAlbum == 5 }"
                                class="album-list__item">album4</a>
                            <a href="#" @click="activeAlbum = 6" :class="{ active: activeAlbum == 6 }"
                                class="album-list__item">album56</a>
                            <a href="#" @click="activeAlbum = 7" :class="{ active: activeAlbum == 7 }"
                                class="album-list__item">album8</a>
                            <a href="#" @click="activeAlbum = 8" :class="{ active: activeAlbum == 8 }"
                                class="album-list__item">album0</a>

                            <a class="album__nav-link" href="#"><img src="../assets/left_arrow.svg"
                                    alt="left_arrow"></a>
                            <a class="album__nav-link" href="#"><img src="../assets/right_arrow.svg"
                                    alt="right_arrow"></a>
                        </div>

                    </div>
                    <div class="track-list">
                        <div class="track active">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                Hollow Point 2.0
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                A New Star Would Rise
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                If the Last Star Fell
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                Hollow Point 2.0
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                A New Star Would Rise, O la la, Echoes of War, O la la, Olalotris
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                Hollow Point 2.0
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                A New Star Would Rise
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                If the Last Star Fell
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                Hollow Point 2.0
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                A New Star Would Rise, O la la, Echoes of War, O la la, Olalotris
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                A New Star Would Rise, O la la, Echoes of War, O la la, Olalotris
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                A New Star Would Rise, O la la, Echoes of War, O la la, Olalotris
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                A New Star Would Rise, O la la, Echoes of War, O la la, Olalotris
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                A New Star Would Rise, O la la, Echoes of War, O la la, Olalotris
                            </span>
                        </div>
                        <div class="track">
                            <div class="play">
                                <div class="play__btn"></div>
                            </div>
                            <span class="name-track">
                                A New Star Would Rise, O la la, Echoes of War, O la la, Olalotris
                            </span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<script>

export default {
    data() {
        return {
            activeGenre: 1,
            activeAlbum: 1,
            // tracks:{
            //     track:{
            //         id:1,
            //         genre:'rock',
            //         album:'album1',
            //         src:'../assets/music',
            //     },
            //     track:{
            //         id:2,
            //         genre:'acoustice',
            //         album:'album1',
            //         src:'../assets/music',
            //     },
            //     track:{
            //         id:3,
            //         genre:'rock',
            //         album:'album1',
            //         src:'../assets/music',
            //     },
            //     track:{
            //         id:4,
            //         genre:'rock',
            //         album:'album1',
            //         src:'../assets/music',
            //     },
            // }
        }
    },
    methods: {

    }
}
</script>

<style scoped>
.player__main {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 180px;
}

.player__info {
    z-index: 4;
    position: absolute;
    top: 28%;
    left: 22%;

    text-align: center;

    display: flex;
    flex-direction: column;
    align-items: center;
}

.main_player {
    z-index: 2;
    position: relative;
    display: inline-block;
}

.player__controls {
    margin-top: 10px;

    display: flex;
    align-items: center;
}

.player__controls>* {
    cursor: pointer;
}

.player_name-track {

    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 300;
    font-size: 20px;
    color: #fff;
}

.track-time {
    margin-top: 25px;

    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 300;
    font-size: 13px;

    color: #fff;
}

.previous,
.play,
.next {
    margin: 10px;
}

hr {
    opacity: .4;
}

.active {
    opacity: 1 !important;
    color: #F0503A;
}

.album-list {
    display: inline-block;
}

.genre-music__item,
.album-list__item {
    display: inline-block;

    opacity: .4;

    margin-right: 40px;
    margin-bottom: 20px;
    margin-top: 20px;
}

.album__nav-link {
    margin-inline: 16px;
}

.play {
    min-width: 32px;
    height: 32px;
    background-color: #FF4A37;
    border-radius: 100%;

    cursor: pointer;
}

.play__btn {
    position: relative;
    top: 25%;
    left: 37%;

    width: 0;
    height: 0;

    border-style: solid;
    border-width: 7.5px 0 7.5px 12px;
    border-color: transparent transparent transparent #FFC3B0;
}

.track-list {
    overflow-y: scroll;
    max-height: 280px;

    display: grid;
    grid-template-columns: repeat(2, 50%);
}

.track-list::-webkit-scrollbar {
    width: 4px;
}

.track-list::-webkit-scrollbar-track {
    background: #e2e2e2;
}

.track-list::-webkit-scrollbar-thumb {
    width: 4px;
    background-color: #F0503A;
}

.track {
    display: flex;
    align-items: center;

    margin-top: 10px;

    max-width: 350px;


}

.name-track {
    margin-left: 5px;

    cursor: pointer;
}

:not(.active)>.play>.play__btn {
    opacity: .6;
}
</style>
