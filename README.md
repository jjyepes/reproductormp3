<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href="player.css" rel="stylesheet" type="text/css" />
    <title>my music</title>
  </head>
  <body>
    <div class="player">
      <div class="player__header">
        <div class="player__img player__img--absolute slider">
          <button class="player__button player__button--absolute--nw playlist">
            <img
              src="http://physical-authority.surge.sh/imgs/icon/playlist.svg"
              alt="playlist-icon"
            />
          </button>
          <button class="player__button player__button--absolute--center play">
            <img
              src="http://physical-authority.surge.sh/imgs/icon/play.svg"
              alt="play-icon"
            />
            <img
              src="http://physical-authority.surge.sh/imgs/icon/pause.svg"
              alt="pause-icon"
            />
          </button>
          <div class="slider__content">
            <img
              class="img slider__img"
              src="http://physical-authority.surge.sh/imgs/1.jpg"
              alt="cover"
            />
            <img
              class="img slider__img"
              src="http://physical-authority.surge.sh/imgs/2.jpg"
              alt="cover"
            />
            <img
              class="img slider__img"
              src="http://physical-authority.surge.sh/imgs/3.jpg"
              alt="cover"
            />
            <img
              class="img slider__img"
              src="http://physical-authority.surge.sh/imgs/4.jpg"
              alt="cover"
            />
            <img
              class="img slider__img"
              src="http://physical-authority.surge.sh/imgs/5.jpg"
              alt="cover"
            />
            <img
              class="img slider__img"
              src="http://physical-authority.surge.sh/imgs/6.jpg"
              alt="cover"
            />
            <img
              class="img slider__img"
              src="http://physical-authority.surge.sh/imgs/7.jpg"
              alt="cover"
            />
          </div>
        </div>

        <div class="player__controls">
          <button class="player__button back">
            <img
              class="img"
              src="http://physical-authority.surge.sh/imgs/icon/back.svg"
              alt="back-icon"
            />
          </button>
          <p class="player__context slider__context">
            <strong class="slider__name"></strong>
            <span class="player__title slider__title"></span>
          </p>
          <button class="player__button next">
            <img
              class="img"
              src="http://physical-authority.surge.sh/imgs/icon/next.svg"
              alt="next-icon"
            />
          </button>
          <div class="progres">
            <div class="progres__filled"></div>
          </div>
        </div>
      </div>

      <ul class="player__playlist list">
        <li class="player__song">
          <img
            class="player__img img"
            src="http://physical-authority.surge.sh/imgs/2.jpg"
            alt="cover"
          />
          <p class="player__context">
            <b class="player__song-name">blinding lights</b>
            <span class="flex">
              <span class="player__title">the weeknd</span>
              <span class="player__song-time"></span>
            </span>
          </p>
          <audio
            class="audio"
            src="http://physical-authority.surge.sh/music/2.mp3"
          ></audio>
        </li>
        <li class="player__song">
          <img
            class="player__img img"
            src="http://physical-authority.surge.sh/imgs/3.jpg"
            alt="cover"
          />
          <p class="player__context">
            <b class="player__song-name">????????????????</b>
            <span class="flex">
              <span class="player__title">enrasta</span>
              <span class="player__song-time"></span>
            </span>
          </p>
          <audio
            class="audio"
            src="http://physical-authority.surge.sh/music/3.mp3"
          ></audio>
        </li>
        <li class="player__song">
          <img
            class="player__img img"
            src="http://physical-authority.surge.sh/imgs/4.jpg"
            alt="cover"
          />
          <p class="player__context">
            <b class="player__song-name">a man</b>
            <span class="flex">
              <span class="player__title">travis scott</span>
              <span class="player__song-time"></span>
            </span>
          </p>
          <audio
            class="audio"
            src="http://physical-authority.surge.sh/music/4.mp3"
          ></audio>
        </li>
        <li class="player__song">
          <img
            class="player__img img"
            src="http://physical-authority.surge.sh/imgs/5.jpg"
            alt="cover"
          />
          <p class="player__context">
            <b class="player__song-name">unforgetting</b>
            <span class="flex">
              <span class="player__title">zaxx</span>
              <span class="player__song-time"></span>
            </span>
          </p>
          <audio
            class="audio"
            src="http://physical-authority.surge.sh/music/5.mp3"
          ></audio>
        </li>
        <li class="player__song">
          <img
            class="player__img img"
            src="http://physical-authority.surge.sh/imgs/6.jpg"
            alt="cover"
          />
          <p class="player__context">
            <b class="player__song-name">waharan</b>
            <span class="flex">
              <span class="player__title">Randall</span>
              <span class="player__song-time"></span>
            </span>
          </p>
          <audio
            class="audio"
            src="http://physical-authority.surge.sh/music/6.mp3"
          ></audio>
        </li>
        <li class="player__song">
          <img
            class="player__img img"
            src="http://physical-authority.surge.sh/imgs/7.jpg"
            alt="cover"
          />
          <p class="player__context">
            <b class="player__song-name"
              >starlight feat mr gabriel remix
              <span class="uppercase"></span> </b
            >
            <span class="flex">
              <span class="player__title">jai wolf</span>
              <span class="player__song-time"></span>
            </span>
          </p>
          <audio
            class="audio"
            src="imagt/"
          ></audio>
        </li>
        <li class="player__song">
          <img
            class="player__img img"
            src="imagt/juana bts.jpg"
            alt="cover"
          />
          <p class="player__context">
            <b class="player__song-name">Juana-</b>
            <span class="flex">
              <span class="player__title">-Cypher 4 BTS</span>
              <span class="player__song-time"></span>
            </span>
          </p>
          <audio
            class="audio"
            src="audio}/BTS Cypher 4(MP3_320K).mp3"
          ></audio>
          <li class="player__song">
            <img
              class="player__img img"
              src="imagt/uno.samuel.jpg"
              alt="cover"
            />
            <p class="player__context">
              <b class="player__song-name">samuel-uno</b>
              <span class="flex">
                <span class="player__title">uno redimi</span>
                <span class="player__song-time"></span>
              </span>
            </p>
            <audio
              class="audio"
              src="audio}/UNO _ Redimi2 x Alex Zurdo x Funky Ft. Almighty_ Christian Ponce_ Ander Bock (Video Lyric)(MP3_320K).mp3"
            ></audio>
            <li class="player__song">
              <img
                class="player__img img"
                src="imagt/jeferson.jpg"
                alt="cover"
              />
              <p class="player__context">
                <b class="player__song-name">jeferson</b>
                <span class="flex">
                  <span class="player__title">GUNS n rouses</span>
                  <span class="player__song-time"></span>
                </span>
              </p>
              <audio
                class="audio"
                src="audio}/guns.mp3"
              ></audio>
        </li>
        <li class="player__song">
          <img
            class="player__img img"
            src="imagt/juli.jpg"
            alt="cover"
          />
          <p class="player__context">
            <b class="player__song-name">profe juli</b>
            <span class="flex">
              <span class="player__title">Dayglow</span>
              <span class="player__song-time"></span>
            </span>
          </p>
          <audio
            class="audio"
            src="audio}/dayglow.mp3"
          ></audio>
    </li>
    <li class="player__song">
      <img
        class="player__img img"
        src="imagt/laura.jpg"
        alt="cover"
      />
      <p class="player__context">
        <b class="player__song-name">Laura vega</b>
        <span class="flex">
          <span class="player__title">dont blame me</span>
          <span class="player__song-time"></span>
        </span>
      </p>
      <audio
        class="audio"
        src="audio}/dont bla,e.mp3"
      ></audio>
</li>
<li class="player__song">
  <img
    class="player__img img"
    src="imagt/stefany.out love.jpg"
    alt="cover"
  />
  <p class="player__context">
    <b class="player__song-name">stefany</b>
    <span class="flex">
      <span class="player__title">out of love</span>
      <span class="player__song-time"></span>
    </span>
  </p>
  <audio
    class="audio"
    src="audio}/lil tecca.mp3"
  ></audio>
</li>
<li class="player__song">
  <img
    class="player__img img"
    src="imagt/juanjo.jpg"
    alt="cover"
  />
  <p class="player__context">
    <b class="player__song-name">9 simfonia de Beethoven</b>
    <span class="flex">
      <span class="player__title">juan yepes</span>
      <span class="player__song-time"></span>
    </span>
  </p>
  <audio
    class="audio"
    src="audio}/Beethoven 9na-Sinfonia(MP3_70K).mp3"
  ></audio>
</li>
<li class="player__song">
  <img
    class="player__img img"
    src="imagt/moises.jpg"
    alt="cover"
  />
  <p class="player__context">
    <b class="player__song-name">profe moises</b>
    <span class="flex">
      <span class="player__title">Rapdoddy of fire</span>
      <span class="player__song-time"></span>
    </span>
  </p>
  <audio
    class="audio"
    src="audio}/rapsody of fire.mp3"
  ></audio>
</li>
<li class="player__song">
  <img
    class="player__img img"
    src="imagt/no lie.jpg"
    alt="cover"
  />
  <p class="player__context">
    <b class="player__song-name">Geraldine</b>
    <span class="flex">
      <span class="player__title">no lie</span>
      <span class="player__song-time"></span>
    </span>
  </p>
  <audio
    class="audio"
    src="audio}/sean paul.mp3"
  ></audio>
</li>
      </ul>
    </div>
    <script src="/player.js"></script>
  </body>
</html>
