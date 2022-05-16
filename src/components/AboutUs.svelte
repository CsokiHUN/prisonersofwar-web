<script>
  import charArcher from '../assets/war_characters_archer.png';
  import charWarrior from '../assets/war_characters_warrior-1.png';
  import charMage from '../assets/war_characters_mage.png';
  import units from '../assets/war_units.jpg';
  import wolf from '../assets/war_picture_wolf.jpg';
</script>

<div id="aboutus" class="mb-16">
  <h3 class="text-3xl text-center">About us</h3>
  <div class="flex justify-center mt-2">
    <div class="h-1 w-28 bg-red-800" />
  </div>

  <div class="px-32">
    <div class="grid grid-flow-row lg:grid-cols-3 gap-20 justify-center mt-10 mb-32">
      <div>
        <img src={charArcher} alt="" class="m-auto" />

        <h5 class="font-bold">Competitive, 18+ guild.</h5>

        <p>
          We are an active, friendly, and competitive 18+ guild, but we can make exceptions for younger players if we believe that we will
          provide the safe environment they deserve. We have VERY competitive members and slots the are filling, so don't get left behind.
        </p>
      </div>

      <div>
        <img src={charWarrior} alt="" class="m-auto" />

        <h5 class="font-bold">Friendly Guild Management</h5>

        <p>
          The guild leaders are called Chieftains. They create a non-toxic community, but where everyone is encouraged to discuss and
          interact.
        </p>
      </div>

      <div>
        <img src={charMage} alt="" class="m-auto" />

        <h5 class="font-bold">Social platforms</h5>

        <p>For more content about the guild and the game, follow our Twitter, Twitch and Discord down below.</p>
      </div>
    </div>

    <div class="grid  lg:grid-cols-2 gap-10 justify-center mt-20">
      <div>
        <span class="font-bold">Our rules</span>
        <h3 class="text-3xl font-bold">Important rules you may want know.</h3>

        <div class="mt-5 flex flex-wrap justify-center">
          <img src={units} alt="" class="w-11/12 border-4 border-black" />
          <img src={wolf} alt="" class="w-11/12 mt-7 border-4 border-black" />
        </div>
      </div>
      <div>
        <h3 class="text-3xl font-bold">Game rules</h3>

        <p class="mt-1">
          Botting, account-sharing, gold-buying, and any exploits which are against the Blizzard TOS will result in a swift investigation by
          the Chieftains (equivalent to a leader/admin) and likely an instant kick from our guild.
        </p>

        <h3 class="text-3xl font-bold mt-10">Raids/Dungeons/PvP rules</h3>

        <p class="mt-1">
          If you’re doing raids, dungeons, or PVP with us, we expect you to be always on time. When creating events, will be clear in our
          timings, bearing in mind different time zones. If you cannot show up on time for any reason, please inform a relevant person
          in-game or on discord as soon as you can.
        </p>

        <h3 class="text-3xl font-bold mt-10">Cash Shop Requirements</h3>

        <p class="mt-1">
          Even though we absolutely respect our member's right to a F2P experience, we honestly expect any game-breaking advantages to be
          purchased in the shop. We are talking about permanent gold/exp boosts only, which would seriously hinder your progress if not
          acquired. We don't expect this cost to be too high, especially as these are probably well-spaced, rare, and relatively affordable
          purchases. Nobody here is Elon Musk, but we want to be strong enough to compete in PVE and PVP. If you are not able to purchase
          these great value deals, please be honest with everyone and join a more casual guild.
        </p>
      </div>
    </div>
  </div>
</div>
