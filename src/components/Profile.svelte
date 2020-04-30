<script>
  export let nickname;
  export let name;
</script>

<style>
  .Profile__content {
    display: flex;
    align-items: center;
  }
  .Profile__avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile__info {
    margin: 0 0 0 0.5em;
  }
  .Profile__info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile__info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>

<div class="Profile">
    <div class="Profile__content">
        <div class="Profile__avatar">
            <img src="https://lh3.googleusercontent.com/l5GpkWT7IAtyIQXtnevd_Eu9XC56uuln5bzCFKmIc0tQVK0uKtrLYRSrd7UCpNuP0NQ2jSSWbXEZlICFbkbLUFvC6ZzDn1i_PwhIhh4qAsd5KNW5zu_9p7aCSfNXiWwE_Vk0kVM6lAu6hhw5Qie3atY-qqG0snehpdReKlQuZGbCHgFkVQyjW3OvcoJuEPwJKTSuFZvk_KCdzrlOV3ilfitgTmhe-0j-iphK3paoGtYF_SJskcebLCY-POompk8roiujlFSCqDy6mimAuaUVs571Mbs5T4iKOuavCI1-qSK9nDTeev5G2GTxLLsyKl0ZEeDbY3B98WxvRDS5tk3xRuS-PZd_M2_ZXDUgGr637T8rOlkZFzvx9iKwk2Q1LvY9Kh5rufWHCIot7aMj3fDo67TeEidUBlinoWYnyh_cpfnhggIuJUHA-OqYV8VLojQQ3_dsG07QU-eNzR2m7k6K_hWYyCgrksvfvF7ehdon-EaEOOaa9zFAaomRAEnbd5u3VAj3zfdD4eWvXuZ3oNpD9kaFFj68SuO4g8kF-Ul4UU-hkrcyChJsapAooD7eavpJ2SXSpkRMn_EDTzGb91lD2uYEXl0P2AYUjmfcxHALlIbr5p8ZEhserlVV3UeAx5-dG5Sv53i5PhIec_L9NtLWyPz852EqJb96h3KRS3IKNk3JDAqJOqMUtKPvMlP0nC0=w466-h621-no" alt="Avatar">
        </div>
        <div class="Profile__info">
            <h2> {nickname} </h2>
            <span> {name} </span>
        </div>
    </div>
</div>