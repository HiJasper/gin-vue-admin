<template>
    <div>
        <div style="width: 100%">
            <APlayer :audio="audio"></APlayer>
        </div>
    </div>
</template>

<script>
    import { APlayer } from '@moefe/vue-aplayer';
    export default {
        name: "musicPlayer",
        components:{
            APlayer
        },
        data(){
            return {
                audio :[
                    {
                        name: '东西（Cover：林俊呈）',
                        artist: '纳豆',
                        url: 'http://music.163.com/song/media/outer/url?id=1321594530.mp3',
                        cover: 'https://p1.music.126.net/5zs7IvmLv7KahY3BFzUmrg==/109951163635241613.jpg?param=300y300', // prettier-ignore
                        lrc: 'https://cdn.moefe.org/music/lrc/thing.lrc',
                    },
                    {
                        name: '响喜乱舞（Cover：MARiA）',
                        artist: '泠鸢yousa',
                        url: 'http://music.163.com/song/media/outer/url?id=1318962459.mp3',
                        cover: 'https://p1.music.126.net/AUGVPQ_rVrngDH9ocQrn3Q==/109951163613037822.jpg?param=300y300', // prettier-ignore
                        lrc: 'https://cdn.moefe.org/music/lrc/kyoukiranbu.lrc',
                    },
                    {
                        name: '啵唧',
                        artist: 'Hanser',
                        url: 'http://music.163.com/song/media/outer/url?id=1321424246.mp3',
                        cover: 'https://p1.music.126.net/K0-IPcIQ9QFvA0jXTBqoWQ==/109951163636756693.jpg?param=300y300', // prettier-ignore
                        lrc: 'https://cdn.moefe.org/music/lrc/kiss.lrc',
                    },
                ]
            }
        }
    }
</script>

<style scoped>

</style>
