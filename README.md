<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" type="text/css" href="3.css">
</head>
<body>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat&family=Poppins:wght@600&display=swap');

body{
    height: 80vh;
    justify-content: center;
    align-items: center;
    font-family: 'Poppins', sans-serif;
    background-image: linear-gradient(to right, #4daf54, #3d8888);
    display: flex;
}
.card{
    width: 300px;
    height: 450px;
    color: white;
    border-radius: 10px;
    padding: 50px;
    background-color: black;
}
.card_avt{
    width: 190px;
    height: 200px;
    border-radius: 50%;
    overflow: hidden;
    
    background-color: aliceblue;
    margin-left: 50px;
    border: 3px solid #4daf54;
}

.name{
    margin-top: 10px;

    margin-left: 65px ;
    font-size: 30px;
}

.descript{
    margin-left:  55px;
    
    color: #2fb484;
    font-family: 'Montserrat', sans-serif;
}

.icon{
    padding: 2px 5px;
   
    align-items: center;
    display: flex;
    margin: 50px 0;
}

 .phone, .zalo, .tele, .dis{
    margin-left: -10px;
    margin-right: 80px;
    align-items: center;
    display: flex;
    
 }

 .phone:hover{
    outline:1px outset  #0c572e  ;
    transition: 0.3s;

 }
 .zalo:hover{
    outline:1px outset  #0c572e  ;
    transition: 0.3s;

 }
 .tele:hover{
    outline:1px outset  #0c572e  ;
    transition: 0.3s;

 }
 .dis:hover{
    outline:1px outset  #0c572e  ;
    transition: 0.3s;

 }

 .more button{
    align-items: center;
    background-color: black;
    border-radius: 10px;
    width: 125px;
    height: 50px;
    border: none;
    outline: 2px solid #2fb484;
    color: aliceblue;
    margin: 0 10px;
 }
 .more button:hover{
    background:#0c572e ;
    transition: 0.3s;
 }

    </style>
    <div class="card">
        <div class="card_avt">
            <img src="https://scontent.fhph1-2.fna.fbcdn.net/v/t39.30808-6/347838927_200476546246155_7328945691959368176_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=a2f6c7&_nc_ohc=-1NIg3TzGd4AX-RJlmF&_nc_ht=scontent.fhph1-2.fna&oh=00_AfCax39ShSnzSJcPZ61mZhlIEQVm3Wt0JIOkqE5q7XiHrw&oe=650427A7" width="200px" height="200px">
        </div>
        <div class="in4"> 
            <div class="name">Vu thu hien</div>
            <div class="descript">Blogger & Digital creator</div>
            <div class="icon">
                <span class="phone">
                    <a href="phone.jpg"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAW1JREFUSEu1lY1xgzAMhZ/MImSSkkmaTJJ0kpBJSidpFsHqSf4JYEwxHL7LXY7E+qQnPUE4+NDB8TELYOYazA8ANYjORPTamkgCGARvfNDXHsgIMAkesq4BbIaMAX3/ANFFApIxJw/8Vqk2QsYAa1lkIWPi8ylEwCX9mAJ+fWNPobET2Toy5rwHIHI0vqmdBGJr3TMvW0lwVWN4gfv+BqI7mO9UVV8eEKqScVVoyZlOUQNmyVibrIDQeOaWqupaEjytwBnMTY0zWOd7IFXIqF5Lq0iNFmQCYkOjdJNRXeP4nJMlY/iM28SAzB2MeYL55gdA/j1rxtwuuvhdFC8pxNpPHYLxWXR8dpsuyvIG/ev4POC9UdUDcFOkozt3co5ffB8ksjC3ov3cJOUcv+qFM5ArJK8VwZgfrU4No++PxPGrAO5+bLJsW9mucycaNPy4GhAuKEgytfYDRPLdfQbrZUguBuxaFaWX1/z/8Ar+ADew/Bm4EtkJAAAAAElFTkSuQmCC">
                    </a>
                </span>
                <span class="zalo">
                    <a href="zalo.jpg"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAACXBIWXMAAAsTAAALEwEAmpwYAAAEXUlEQVR4nO2ZW08bRxTHl/aTpFI/QNI+5aGR+tIPkPDWVupnqNiLZ4xvmEvSEERJCGkSkl5QFRPSJCUEArgkweRCakMLNpLtQgw2YO8sStrSPJ3qLFl3bbxm11ek+khHtmeP1//fzJmZs2OOa1jDGvb/MwBo2tnZ+YAx5pBl2c8YW2GM/ckYA5OOsWH8rizLLkVRjtVEeHNz87uk1fnZs+fzigWxZj2SyWROYedURfyXhBzhJToz8WCy0sIhz+cURTlSUfGCQD4WJPrqyuB1kGW52gAgy3KaMXaiIuJ5m/0TQaL/OFxtsL6+XnXx7D+IN2VDtFD6viASRZAoTE5N10w8041EyenkcDje4SXyBMW3tXfB9vZ2zQHYngdKmti8SL5A8ej3xyfqJR7QM5nMyRIA6BKKt1FHTXOfFfawJfGCQD7Ser//4qV6iwd0RVGOmgcQacdhSR/21mVZdppPH4nOaADB0MJhAZgyPwISSWgAL18m6i6e7XnEAgD9WwMotHye7x9Qrxl5NBY7UBDG3f151ArAaysAWTHpdHrfzfz+GRj56XaOn/6qW42/4buZjQsGQzA2Ng4zDx9BMplUP8fjfxgCBN/GT/t/KbjylQSQSqUO7J35Fy9AIq0wcOkyrtkq9NXB6zmjgqWIXrT+fbpAvMvjhV+DofIBEonicyAcjgBtdcGZsz1Z2Dt3R0G02WF84gEkUymIRFagu6fXEOCOQbzL054zEiUBxGJxQ/E4wbHM8Hg7YG1tLdvubmsHrFxzQCMRQwB3kXhM17IAlsPhguK3trag+1wvELsTlpdzY7DNNzyS04ZzwAiAFInHOVEWQGDuyT7x+Exw+eo1ddifPn2273rfhYvg7ehS00Frw/QwAugrEh/S7UMlAWB+5gvElQavnev5Wu0hvc/OBtR5gTUUisKe1WCNAMIG8YPXvi1/EuffBNf4YnuAlssoCnsWhXV0nlE7wun2ZkXr3zNdPKaTx9upXstfwksC6Dp91spmU1XnSgEwu7MeNoBXegCLW361/C/TALxEV/QAbe2dBUuKWrosy6vmR0Ak0/lpNDnlrzfAtPkREKkrHwB3y42NjXoCuE0DtNhsxwotkd99P1RPgOOmATiOaxJEEskHwM1lc3OzHuIXrIjfSyOJnsoHwJK5TpP5U8sAe6NA5/QA9TihWF1djZZ8Yo0n0oJE0tr5UH7VmUisQzQarYrwVCoF98bu7w75fB9y5ViLZD/Bi+TND0M/QmhhEZ7Pz8PovTHoO9+fLdCw3MBjdyyByxGdTqfVp7AbvmFodXl28VS8LPF6CG0kijkWYr19F2D45i2YDczB4uJvEIvHVTDtcABf8SkL239fWoKHjx7DyK3bMPDNFbA73Op9eImyionP/YODBA6CKNd5kTwWRcd7XJWsSRBsJ3mRhisvnC4JNvo5/gZXCxMEelSQiJOX6BQC8SJ5baGXd3mRJvG7gki7eEKO10x4wxrWMO5Q2b9IkHplg7DTsgAAAABJRU5ErkJggg=="width="24px" height="24px">
                    </a>
                </span>
                <span class="tele">
                    <a href="tele.jpg"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAyCAYAAAAeP4ixAAAACXBIWXMAAAsTAAALEwEAmpwYAAADYklEQVR4nO2YW4hNURjHl2tEElEiJblECg8u5WFSXjBSGDwqyuVFUQpJKZdyaUpKSkJTyuVNEw+EB0V4cBvK5DbT4TTr/19njjFjWPrMOtlO57bPWfucMzr/Wk9n7/V9v73+6ztrfUrVVFNNNdXkWcaYcQD2AngOoBvAQ2PMTNVfpLWeD+A8gC6SNm3cUdUsa+0QAA0A7mdIPjg6VBXbZx+AT3kAUuOtqiZpreeRPAvgW4EAfwaAG9Vgn0Ek60neDpM8/wU5UDGARCIxHsAeku+LBeDfsbIi1SeMfQB8A9CS65lkMjmxqu0D4AXJQwB+5ngmVk77fCjC9xdJLgfwPc+zzVVjn7RBABsSicQckrqA549E8ee1rpTqQ/IRgKnxeHwSyY8FrlxDxe0TSOYXgEZr7VCSYwG8CvH+tEraJwjxleQKt6rDATwIY0Nr7cDQycsX82CfIMTdVOmUygbgesj375XdPmkJSDk9KsmnYpA8XcQ8jYUCzAZwSc79PgBc8M9a67pgHJIHi5xvU14IY8xqAD2+ABzETTnZBuNorbcUO5/Wem5eEADtHgHkg+y21g5IW4l6AD+KnPO7lPxCQGKeQN6RXJg+P8nFJJMlzPs4L4QD2eoB4qrWenQGiBkA4iWu8rmCQFzAVSSfFhGkC8C2THN2dnZOINnqwa7bVVhpradI+QXwsoAAr7Ntwng8PorkE0+WXaRKkZRkKZcA3mSAuBiLxUZmek82JslbPiAA9La3t49QviSbGMBJkgkXZHoWiIEkmzythBVnqCgE4IILsivL7yd8QbBvXI4ERGu9JlujTPaLZwib7YOVLNkXrlL1yjE8+BuAU75BtNZLVVSSK6fz78a0y9YXnxDou7uMiQwEwA4XrCl4XovAVq0qSnV0dEyWryVX7tQZSDqAvkEAXFNRi+Qz5+E617/tiQBkfzlADrlgx0nuzJHM66ruKgJY4BJtyXZGA3BMjvMCWsyKJcvRVZQE5QaYo9rsCT5vjFkCoC2ErWKqXJLOSoYEeo0xm7OdhqWJUCBMc9lAUvYKQHTna6JZawdLM8JVvVwgh1U5JZceB9EGYFmI99YHDqA2fWit16pySzaltXZY2PeMMbMyVTUAz6WvpvqT3AXsjOsbSCP7iuylSudVU03qP9FvK11c+H/OyYUAAAAASUVORK5CYII="width="24px" height="24px">
                    </a>
                </span>
                <span class="dis">
                    <a href="dis.jpg"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAyCAYAAAAeP4ixAAAACXBIWXMAAAsTAAALEwEAmpwYAAADpUlEQVR4nO1Y24uNURQfQ+NSCpNLeJZ7GHlQLk8kt/DAEw+ivIlyKy/yBzBjnki55IFCIo/jlkGNyzCFQowRzTj799vfOXLctlazTz7nfLfzzXdmjnyrVp2+s9dvrd9ea99WTU0qqaSSSir/kpCcAmA7gOMkH5LUAG4YYwaF2coYki1iI7aCIVgkp/RL8LlcbhKAgwBekjQFBZAHcAfAUQCjw3CUUqMAHLE2+SKsF+JDfCVOwHGccSSPAfjqcii/z2mt13V3d4+Miy22giFYKMVvFt+JkCC5CsAn16xlAOwjWV9EdqbWeivJJgBXAXTYsT9E7e8O+U/GyFjHcWYU+aq32BkXIfG9qq8kFgL45iLR5C4dAPNl1ki+c5dHmfrOZrvBhTtavrmzA2BBLBLGmMF2Vgtg340xddbRcpIP+hC8n94HsMz6r7OZLPz3yBhTGycbmz0ctQC4VQECfymA2wBuenzfWDYRAO2VDjiGPiyLhNZ6cRUEbXyyFX2tADhTxURORCJhjBnGXjFVqsoYMzSUiFJqfRUEa0J0dSgRkmerIFATUl6nwsqqtugUr0oF8DHwcqqUmjfQQTKiZjKZ2b5EAOyNMTt3lVJzZAEqpeYCaK2EDUt1dxCRK2WCPS5cW1zlWUfyScI2xmMyLgYR+ZDE7qG1XpuwjfHQTk8SPT09k8tNr99bQWs9Nkkb+mgul5tYAkRyTQwi472Cku9J2tBfS98pJHfFAFoTo0zi2Bgf3elFpDkGkOfCDbk5x7ExPtrkReR6DCDZPVrl/JE7mrzyANyrhA29ca6VEAHwLA7YQCqAdq+MvB3owFi+vvEi8jmA+S95MwP42Y+z/VMOSevbb0yPV2nlAwyO251lSXFzrkIkXiqlltq4TgSMy3tlpC3A4Gk2m51gd5ghtr3ZWQESnUqpbeJDfInPkLXbVkJEaz2NZDaATLd0VgrXZ3vh2wDgcpBdBHUAXJIHnbHbsu0Nb5HSCbLTWk8tIWKzsjIsKNkppC3j7jFJAFIKWus9AE7a2+wrCcT2hfM2KPnWKmNkrJSq+0wxvb20TRHOFIfkCk8SrrXSILtBhDp+T7JRa70oVuPsT/C1tmvTCKArQgZfyxkUCbyrq2sEycMkcxEIfdFaT49LRGwFIwKBLMlDxpjhZTuxTeUD0uoPILKjpo8iGAH4zwHsBzCmJglxHGeWXNJIXrCPoGxoE6AMAXDazrpgnxdf0uFPCj+VVFJJJZVU/gv5Dar1tqjR1cllAAAAAElFTkSuQmCC"width="24px" height="24px">
                    </a>
                </span>
      
            </div>
            <div class="more">
                <a href="https://www.facebook.com/thuu.hhien.2704?locale=vi_VN"><button>Contact me</button></a>

                <button> See more</button>
            </div>
        </div>
        

    </div>
    
</body>
</html>
