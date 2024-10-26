let songName=document.querySelector("#song-name")
let songSinger=document.querySelector("#song-singer")
let songImage=document.querySelector(".song-image")
let playPauseImg=document.querySelector("#play-pause")
let volumeRange=document.querySelector("#volume-range")
let songRange=document.querySelector("#song-duration")
let volSvg=document.querySelector("#vol-svg")
let musicAnim=document.querySelector("#musicanim")
let playlistImg=document.querySelector("#playlist-img")
let playlist=document.querySelector(".playlist")
let playlistSong=document.querySelectorAll(".playlist-song")
let index=0;
let playingSong=false;
let track=document.createElement("audio")
let songs=[
    {
        name:"1.REMIX 2024",
        path:"1.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"2.REMIX 2024",
        path:"2.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"3.REMIX 2024",
        path:"3.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"4.REMIX 2024",
        path:"4.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"5.REMIX 2024",
        path:"5.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"6.REMIX 2024",
        path:"6.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"7.REMIX 2024",
        path:"7.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"8.REMIX 2024",
        path:"8.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"9.REMIX 2024",
        path:"9.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"10.REMIX 2024" , 
        path:"10.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"11.REMIX 2024" , 
        path:"11.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"12.REMIX 2024" , 
        path:"12.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"13.REMIX 2024" , 
        path:"13.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"14.REMIX 2024" , 
        path:"14.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"15.REMIX 2024" , 
        path:"15.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"16.REMIX 2024" , 
        path:"16.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"17.REMIX 2024" , 
        path:"17.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"18.REMIX 2024" , 
        path:"18.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"19.REMIX 2024" , 
        path:"19.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"20.REMIX 2024" , 
        path:"20.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"21.REMIX 2024" , 
        path:"21.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"22.REMIX 2024" , 
        path:"22.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"23.REMIX 2024" , 
        path:"23.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"24.REMIX 2024" , 
        path:"24.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"25.REMIX 2024" , 
        path:"25.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"26.REMIX 2024" , 
        path:"26.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"27.REMIX 2024" , 
        path:"27.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"28.REMIX 2024" , 
        path:"28.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"29.REMIX 2024" , 
        path:"29.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
    {
        name:"30.REMIX 2024" , 
        path:"30.mp3",
        image:"img1.jpg",
        singer:"សូមអរគុណសម្រាប់ការចូលស្តាប់"
    },
]
function loadTrack(index){
track.src=songs[index].path;
songName.innerHTML=songs[index].name;
songSinger.innerHTML=songs[index].singer;
songImage.style=`background-image: url("${songs[index].image}");`
volume()
setInterval(()=>{
songRange.max=track.duration
songRange.value=track.currentTime
},1000)
track.loop=true
track.load()
}
loadTrack(index);

function playPause(){
    if(playingSong==false){
        playSong()
       
    }else{
        pauseSong()
       
    }
}
function playSong(){
    track.play();
    playingSong=true;
playPauseImg.src="pause.svg"
 musicAnim.style.display="block"

}
function pauseSong(){
    track.pause();
    playingSong=false;
playPauseImg.src="play.svg"
 musicAnim.style.display="none"
}
function nextSong(){
    if(index<songs.length-1){
        index++;
        loadTrack(index)
        playSong()
    }else{
        index=0;
        loadTrack(index)
        playSong()
    }
}
function previousSong(){
    if(index>0){
        index--;
        loadTrack(index)
        playSong()
    }else{
        index=songs.length-1;
        loadTrack(index)
        playSong()
    }
}
function volume(){
track.volume=volumeRange.value/100;
if(volumeRange.value==0){
    volSvg.src="mute.svg"
}else{
    volSvg.src="volume.svg"
}
}
function duration(){
    track.currentTime=songRange.value
}
playlistImg.addEventListener("click",()=>{
playlist.classList.toggle("playlist-active")
if(playlist.classList.contains("playlist-active")){
    playlistImg.src="cross.svg"
}else{
    playlistImg.src="playlist.svg"
}
})
playlistSong.forEach((song,index)=>{
    song.addEventListener('click',()=>{
        loadTrack(index);
        playSong()
        playlist.classList.remove("playlist-active")
        playlistImg.src="playlist.svg"

    })
})
