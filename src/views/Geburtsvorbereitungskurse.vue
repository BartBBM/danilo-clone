<template>
  <h1>Geburtsvorbereitungskurse</h1>
  <div class="columns">
    <div>
      <h4>
        Der Geburtsvorbereitungskurs dient dazu, Dich/Euch optimal auf die
        Geburt Deines/Eures Kindes vorzubereiten. Dort erfahrt Ihr alles
        Wichtige, das Ihr braucht, und könnt Eure Fragen stellen.
      </h4>
      <p>
        Optimalerweise beginnst Du den Geburtsvorbereitungskurs zwischen der 22.
        und 27. SSW.
      </p>
      <p>
        Der Geburtsvorbereitungskurs kostet für Dich als Schwangere nichts, da
        er vollständig von der Krankenkasse übernommen wird. Der
        Partner*innenbeitrag kann bei den meisten Krankenkassen eingereicht
        werden und wird bis zu einem bestimmten Betrag übernommen (variiert je
        nach Krankenkasse).
      </p>
      <p>
        Wenn Du privat krankenversichert bist, kontaktiere bitte Deine
        Krankenkasse vorher, ob diese die Kosten übernimmt.
      </p>
      <p>Der Partner*innenbeitrag beträgt 85€</p>
      <p>Selbstverständlich ist die Teilnahme auch ohne Partner*in möglich.</p>
      <p>
        Ein Kurs besteht aus sieben aufeinanderfolgenden Terminen, die jeden
        Dienstag zwischen 19 und 21 Uhr stattfinden.
      </p>
      <p>
        Die Größe der Kurse ist auf maximal 10 Paare/Teilnehmerinnen beschränkt.
      </p>
    </div>
    <div><img src="@/assets/schrank.png" alt="Bücher und Hüfte" /></div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Geburtsvorbereitungskurse",
});
</script>

<style scoped lang="scss">
.columns {
  display: flex;
  flex-wrap: wrap;
  gap: 2em;
}
.columns > * {
  flex-basis: 600px;
  flex-shrink: 1;
  flex-grow: 0.75;
}
</style>
