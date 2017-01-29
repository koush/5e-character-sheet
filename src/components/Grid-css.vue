<template>
  <div class="grid  page">

    <div class="layout">

      <!-- Character -->

      <div class="name  bg-g  p1">
        <div class="bg-w  p1">
          <h5>{{ name }}</h5>
          <small class="mb0  tt-u">Character name</small>
        </div>
      </div>

      <div class="occupation  bg-g  p1">
        <div class="bg-w  p1">
          <h5>{{ occupation }} Level {{ level }}</h5>
          <small class="mb0  tt-u">Class &amp; Level</small>
        </div>
      </div>

      <div class="race  bg-g  p1">
        <div class="bg-w  p1">
          <h5>{{ race }}</h5>
          <small class="mb0  tt-u">Race</small>
        </div>
      </div>

      <div class="alignment  bg-g  p1">
        <div class="bg-w  p1">
          <h5>{{ alignment }}</h5>
          <small class="mb0  tt-u">Alignment</small>
        </div>
      </div>



      <!-- Stats -->
      <section class="stats">
        <div class="bg-g  p1">
          <div class="bg-w  p1  ta-c  mb1">
            <small class="tt-u  mb1">Strength</small>
            <h5>+3</h5>
            <small>16</small>
          </div>

          <div class="bg-w  p1  ta-c  mb1">
            <small class="tt-u  mb1">Dexterity</small>
            <h5>+3</h5>
            <small>16</small>
          </div>

          <div class="bg-w  p1  ta-c  mb1">
            <small class="tt-u  mb1">Constitution</small>
            <h5>+2</h5>
            <small>15</small>
          </div>

          <div class="bg-w  p1  ta-c  mb1">
            <small class="tt-u  mb1">Intelligence</small>
            <h5>+0</h5>
            <small>11</small>
          </div>

          <div class="bg-w  p1  ta-c  mb1">
            <small class="tt-u  mb1">Wisdom</small>
            <h5>+1</h5>
            <small>13</small>
          </div>

          <div class="bg-w  p1  ta-c">
            <small class="tt-u  mb1">Charisma</small>
            <h5>+2</h5>
            <small>14</small>
          </div>
        </div>
      </section>



      <!-- Skills -->
      <section class="skills  p1">
        <div class="bg-w  p1  mb1">
          <p class="tt-u">+2 Proficiency Bonus</p>
          <p class="">+5 Strength</p>
          <p class="">-1 Dexterity</p>
          <p class="">+4 Constitution</p>
          <p class="">+1 Intelligence</p>
          <p class="">+1 Wisdom</p>
          <p class="">+1 Charisma</p>
          <p class="mb0  tt-u">Saving Throws</p>
        </div>
        <div class="bg-w  p1">
          <p class="">+1 Acrobatics</p>
          <p class="">+1 Animal Handling</p>
          <p class="">+1 Arcana</p>
          <p class="">+1 Athletics</p>
          <p class="">+1 Deception</p>
          <p class="">+1 History</p>
          <p class="">+1 Insight</p>
          <p class="">+1 Intimidation</p>
          <p class="">+1 Investigation</p>
          <p class="">+1 Medicine</p>
          <p class="">+1 Nature</p>
          <p class="">+1 Perception</p>
          <p class="">+1 Performance</p>
          <p class="">+1 Persuasion</p>
          <p class="">+1 Religion</p>
          <p class="">+1 Sleight of Hand</p>
          <p class="">+1 Stealth</p>
          <p class="">+1 Survivor</p>
          <small class="mb0  tt-u">Skills</small>
        </div>
      </section>



      <!-- Armour Class -->
      <section class="armour">
        <div class="bg-g  p1">
          <div class="bg-w  p1">
            <h5>Armour</h5>
            <small class="mb0  tt-u">Armour Class</small>
          </div>
        </div>
      </section>



      <!-- Personality -->
      <section class="personality">
        <div class="bg-g  p1">
          <div class="bg-w  p1">
            <p>Hey</p>
            <small class="mb0  tt-u">Personality Traits</small>

            <p>Hey Two</p>
            <small class="mb0  tt-u">Ideals</small>

            <p>Hey Three</p>
            <small class="mb0  tt-u">Bonds</small>

            <p>Hey Four</p>
            <small class="mb0  tt-u">Flaws</small>
          </div>
        </div>
      </section>



      <!-- Proficiencies -->
      <section class="proficiencies">
        <div class="bg-g  p1">
          <div class="bg-w  p1">
            <p><b>Proficiencies: </b>Shields</p>
            <p><b>Languages: </b>Dwarvish</p>
            <small class="mb0  tt-u">Proficiencies &amp; Languages</small>
          </div>
        </div>
      </section>



      <!-- Attacks -->
      <section class="attacks">
        <div class="bg-g  p1">
          <div class="bg-w  p1">
            <h5>Attacks</h5>
            <small class="mb0  tt-u">Attacks &amp; Spellcasting</small>
          </div>
        </div>
      </section>



      <!-- Features -->
      <section class="features">
        <div class="bg-g  p1">
          <div class="bg-w  p1">
            <h5>Features</h5>
            <small class="mb0  tt-u">Features &amp; Traits</small>
          </div>
        </div>
      </section>



      <!-- Equipment -->
      <section class="equipment">
        <div class="bg-g  p1">
          <div class="bg-w  p1">
            <h5>Equipment</h5>
            <small class="mb0  tt-u">Equipment</small>
          </div>
        </div>
      </section>

    </div>

  </div>
</template>



<script>
export default {
  name: 'grid',
  data() {
    return {
      alignment: 'Chaotic Good',
      name: 'Winston Helldoom Bloodlord',
      occupation: 'Paladin',
      level: '4',
      race: 'Goblin',
    };
  },
};
</script>



<style scoped>

  :root {
    --chamfer-size-s: 4px;
    --chamfer-size-l: 5px;
    --white: #fff;
    --grey-light: #eee;
    --grey-dark: #555;
  }

  .layout {
    display: grid;
    grid-gap: 10px;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-areas:
      "name name name"
      "occupation alignment race"
      "stats skills armour"
      "proficiencies personality personality"
      "equipment features features";
   }

  /* Row 1 */
  .name          { grid-area: name; }
  .occupation    { grid-area: occupation; }
  .race          { grid-area: race; }
  .alignment     { grid-area: alignment; }

  /* Row 2 */
  .stats         { grid-area: stats; }
  .skills        { grid-area: skills; }
  .armour        { grid-area: armour; }
  .personality   { grid-area: personality; }

  /* Row 3 */
  .attacks       { grid-area: attacks; }

  /* Row 4 */
  .proficiencies { grid-area: proficiencies; }
  .features      { grid-area: features; }
  .equipment     { grid-area: equipment; }

  .bg-g {
    background:
      linear-gradient(135deg, transparent var(--chamfer-size-l), var(--grey-light) 0) top left,
      linear-gradient(225deg, transparent var(--chamfer-size-l), var(--grey-light) 0) top right,
      linear-gradient(315deg, transparent var(--chamfer-size-l), var(--grey-light) 0) bottom right,
      linear-gradient(45deg,  transparent var(--chamfer-size-l), var(--grey-light) 0) bottom left;
    background-size: 50% 50%;
    background-repeat: no-repeat;
  }

  .bg-w {
    background:
      linear-gradient(135deg, transparent var(--chamfer-size-s), var(--white) 0) top left,
      linear-gradient(225deg, transparent var(--chamfer-size-s), var(--white) 0) top right,
      linear-gradient(315deg, transparent var(--chamfer-size-s), var(--white) 0) bottom right,
      linear-gradient(45deg,  transparent var(--chamfer-size-s), var(--white) 0) bottom left;
    background-size: 50% 50%;
    background-repeat: no-repeat;
    border: 1px solid #999;
  }

  .oval {
    margin: 0 auto;
    padding-top: 8px;
    width: 40px;
    height: 15px;
    border: 1px solid #000;
    border-radius: 50%;
  }

</style>
