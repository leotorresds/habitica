<template>
  <div class="container-fluid">
    <h1>{{ $t('communityGuidelines') }}</h1>
    <hr>
    <p>{{ $t('lastUpdated') }} February 8, 2023</p>
    <h2 id="welcome">
      {{ $t('commGuideHeadingWelcome') }}
    </h2>
    <div class="media align-items-center">
      <img src="~@/assets/images/community-guidelines/intro.png">
      <div class="media-body">
        <p v-html="$t('commGuidePara001')"></p>
        <p v-html="$t('commGuidePara002')"></p>
      </div>
    </div>
    <p v-html="$t('commGuidePara003')"></p>
    <h2 id="interactions">
      {{ $t('commGuideHeadingInteractions') }}
    </h2>
    <p v-html="$t('commGuidePara015')"></p>
    <p v-html="$t('commGuidePara016')"></p>
    <p v-html="$t('commGuidePara017')"></p>
    <ul>
      <li v-html="$t('commGuideList01F')"></li>
      <li v-html="$t('commGuideList01A')"></li>
      <li v-html="$t('commGuideList01B')"></li>
      <li v-html="$t('commGuideList01C')"></li>
      <li v-html="$t('commGuideList01D')"></li>
      <li v-html="$t('commGuideList01E')"></li>
      <li v-html="$t('commGuideList01F')"></li>
    </ul>
    <div class="media align-items-center">
      <img src="~@/assets/images/community-guidelines/publicSpaces.png">
    </div>
    <ul>
      <li v-html="$t('commGuideList02N')"></li>
      <li v-html="$t('commGuideList02A')"></li>
      <li v-html="$t('commGuideList02B')"></li>
      <li v-html="$t('commGuideList02G')"></li>
      <li v-html="$t('commGuideList02C')"></li>
      <li v-html="$t('commGuideList02D')"></li>
      <li v-html="$t('commGuideList02E')"></li>
      <li v-html="$t('commGuideList02F')"></li>
      <li v-html="$t('commGuideList02M')"></li>
      <li v-html="$t('commGuideList02J')"></li>
      <li v-html="$t('commGuideList02K')"></li>
      <li v-html="$t('commGuideList02L')"></li>
    </ul>
    <p v-html="$t('commGuidePara019')"></p>
    <p v-html="$t('commGuidePara020')"></p>
    <p v-html="$t('commGuidePara020A')"></p>
    <p v-html="$t('commGuidePara021')"></p>
    <h3 id="tavern">
      {{ $t('commGuideHeadingTavern') }}
    </h3>
    <div class="media align-items-center">
      <img src="~@/assets/images/community-guidelines/tavern.png">
      <div class="media-body">
        <p v-html="$t('commGuidePara022')"></p>
        <p v-html="$t('commGuidePara023')"></p>
        <p v-html="$t('commGuidePara024')"></p>
      </div>
    </div>
    <h3 id="guilds">
      {{ $t('commGuideHeadingPublicGuilds') }}
    </h3>
    <div class="media align-items-center">
      <div class="media-body">
        <p v-html="$t('commGuidePara029')"></p>
        <p v-html="$t('commGuidePara031')"></p>
      </div>
      <img src="~@/assets/images/community-guidelines/publicGuilds.png">
    </div>
    <p v-html="$t('commGuidePara033')"></p>
    <p v-html="$t('commGuidePara035')"></p>
    <p v-html="$t('commGuidePara036')"></p>
    <p v-html="$t('commGuidePara037')"></p>
    <p v-html="$t('commGuidePara038')"></p>
    <h2 id="infractions-consequences-restoration">
      {{ $t('commGuideHeadingInfractionsEtc') }}
    </h2>
    <h3 id="infractions">
      {{ $t('commGuideHeadingInfractions') }}
    </h3>
    <div class="media align-items-center">
      <img src="~@/assets/images/community-guidelines/infractions.png">
      <div class="media-body">
        <p v-html="$t('commGuidePara050')"></p>
        <p v-html="$t('commGuidePara051')"></p>
      </div>
    </div>
    <h4>{{ $t('commGuideHeadingSevereInfractions') }}</h4>
    <p v-html="$t('commGuidePara052')"></p>
    <p v-html="$t('commGuidePara053')"></p>
    <ul>
      <li v-html="$t('commGuideList05A')"></li>
      <li v-html="$t('commGuideList05B')"></li>
      <li v-html="$t('commGuideList05C')"></li>
      <li v-html="$t('commGuideList05D')"></li>
      <li v-html="$t('commGuideList05E')"></li>
      <li v-html="$t('commGuideList05F')"></li>
      <li v-html="$t('commGuideList05G')"></li>
      <li v-html="$t('commGuideList05H')"></li>
    </ul>
    <h4>{{ $t('commGuideHeadingModerateInfractions') }}</h4>
    <p v-html="$t('commGuidePara054')"></p>
    <p v-html="$t('commGuidePara055')"></p>
    <ul>
      <li v-html="$t('commGuideList06A')"></li>
      <li v-html="$t('commGuideList06B')"></li>
      <li v-html="$t('commGuideList06C')"></li>
      <li v-html="$t('commGuideList06D')"></li>
      <li v-html="$t('commGuideList06E')"></li>
    </ul>
    <h4>{{ $t('commGuideHeadingMinorInfractions') }}</h4>
    <p v-html="$t('commGuidePara056')"></p>
    <p v-html="$t('commGuidePara057')"></p>
    <ul>
      <li v-html="$t('commGuideList07A')"></li>
      <li v-html="$t('commGuideList07B')"></li>
    </ul>
    <p v-html="$t('commGuidePara057A')"></p>
    <h3 id="consequences">
      {{ $t('commGuideHeadingConsequences') }}
    </h3>
    <div class="media align-items-center">
      <div class="media-body">
        <p v-html="$t('commGuidePara058')"></p>
        <p v-html="$t('commGuidePara059')"></p>
      </div>
      <img src="~@/assets/images/community-guidelines/consequences.png">
    </div>
    <p v-html="$t('commGuidePara060')"></p>
    <ul>
      <li v-html="$t('commGuideList08A')"></li>
      <li v-html="$t('commGuideList08B')"></li>
      <li v-html="$t('commGuideList08C')"></li>
    </ul>
    <p v-html="$t('commGuidePara060A')"></p>
    <p v-html="$t('commGuidePara060B')"></p>
    <h4>{{ $t('commGuideHeadingSevereConsequences') }}</h4>
    <ul>
      <li v-html="$t('commGuideList09A')"></li>
      <li v-html="$t('commGuideList09C')"></li>
      <li v-html="$t('commGuideList09D')"></li>
    </ul>
    <h4>{{ $t('commGuideHeadingModerateConsequences') }}</h4>
    <ul>
      <li>
        {{ $t('commGuideList10A') }}
        <ul>
          <li>{{ $t('commGuideList10A1') }}</li>
        </ul>
      </li>
      <li v-html="$t('commGuideList10D')"></li>
      <li v-html="$t('commGuideList10F')"></li>
    </ul>
    <h4>{{ $t('commGuideHeadingMinorConsequences') }}</h4>
    <ul>
      <li v-html="$t('commGuideList11A')"></li>
      <li v-html="$t('commGuideList11B')"></li>
      <li v-html="$t('commGuideList11C')"></li>
      <li v-html="$t('commGuideList11D')"></li>
      <li v-html="$t('commGuideList11E')"></li>
    </ul>
    <h3 id="restoration">
      {{ $t('commGuideHeadingRestoration') }}
    </h3>
    <div class="media align-items-center">
      <img src="~@/assets/images/community-guidelines/restoration.png">
      <div class="media-body">
        <p v-html="$t('commGuidePara061')"></p>
        <p v-html="$t('commGuidePara062')"></p>
      </div>
    </div>
    <p v-html="$t('commGuidePara063')"></p>
    <h2 id="meet-the-mods">
      {{ $t('commGuideHeadingMeet') }}
    </h2>
    <p v-html="$t('commGuidePara007')"></p>
    <p v-html="$t('commGuidePara009')"></p>
    <div class="media align-items-center">
      <img src="~@/assets/images/community-guidelines/staff.png">
      <div class="media-body">
        <ul>
          <li>
            {{ $t('commGuideAKA', {habitName: 'heyeilatan', realName: 'Natalie'}) }}
            ({{ $t('commGuideOnGitHub', {gitHubName: 'CuriousMagpie'}) }})
            - Web Developer
          </li>
          <li>
            {{ $t('commGuideAKA', {habitName: 'Viirus', realName: 'Phillip'}) }}
            - Mobile Developer
          </li>
          <li>
            {{ $t('commGuideAKA', {habitName: 'redphoenix', realName: 'Vicky'}) }}
            ({{ $t('commGuideOnGitHub', {gitHubName: 'veeeeeee'}) }})
            - Co-Founder
          </li>
          <li>
            {{ $t('commGuideAKA', {habitName: 'Beffymaroo', realName: 'Beth'}) }}
            - Art, Community Management, Many Hats
          </li>
          <li>
            {{ $t('commGuideAKA', {habitName: 'SabreCat', realName: 'Sabe'}) }}
            - Web Developer
          </li>
          <li>
            {{ $t('commGuideAKA', {habitName: 'Apollo', realName: 'Tressley'}) }}
            - Designer
          </li>
          <li>
            {{ $t('commGuideAKA', {habitName: 'Piyo', realName: 'Sara'}) }}
            - Mobile Designer
          </li>
        </ul>
      </div>
    </div>
    <p v-html="$t('commGuidePara013')"></p>
    <p>
      {{ $t('commGuidePara014') }}<br>
      <em>
        Lemoness, lefnire, Slappybag, litenull, Shaner, Bobbyroberts99, wc8,
        Breadstrings, Megan, Blade, Daniel the Bard, deilann, shanaqui, Nakonana,
        Dewines, Alys, Fox_town, MaybeSteveRogers, and Cantras.

      </em>
    </p>
    <h2 id="final">
      {{ $t('commGuideHeadingFinal') }}
    </h2>
    <p v-html="$t('commGuidePara067')"></p>
    <p v-html="$t('commGuidePara068')"></p>
    <h2 id="links">
      {{ $t('commGuideHeadingLinks') }}
    </h2>
    <ul>
      <li v-html="$t('commGuideLink01')"></li>
      <li v-html="$t('commGuideLink02')"></li>
      <li v-html="$t('commGuideLink03')"></li>
      <li v-html="$t('commGuideLink04')"></li>
      <li v-html="$t('commGuideLink06')"></li>
      <li v-html="$t('commGuideLink07')"></li>
    </ul>
    <p v-html="$t('commGuidePara069')"></p>
    <ul class="list-2col list-unstyled">
      <li>Beffymaroo</li>
      <li>Breadstrings</li>
      <li>Draayder</li>
      <li>Kiwibot</li>
      <li>Leephon</li>
      <li>Lemoness</li>
      <li>Luciferian</li>
      <li>Revcleo</li>
      <li>Shaner</li>
      <li>Starsystemic</li>
      <li>UncommonCriminal</li>
    </ul>
  </div>
</template>

<style lang='scss' scoped>
  .list-2col {
    width: 50%;
    columns: 2;
    -moz-columns: 2;
    -webkit-columns: 2;
  }
</style>
