<template>
  <div
    class="w-full h-full grid grid-cols-[1fr_1fr_2fr_2fr_3fr_1fr] grid-rows-[3fr_3fr_3fr_3fr] grid-areas"
  >
    <div class="top-left-corner border-cyan-800 border-2">Top left corner</div>
    <div class="top-fill border-cyan-800 border-2">Top fill</div>
    <div class="top-mid-fill border-cyan-800 border-2">Top mid fill</div>
    <div class="top-right-corner border-cyan-800 border-2">
      Top right corner
    </div>
    <div class="left-fill border-cyan-800 border-2">Left fill</div>
    <div class="impro border-cyan-800 border-2">IMPRO</div>
    <div class="mid-fill border-cyan-800 border-2">Mid fill</div>
    <div class="dates-title border-cyan-800 border-2">Dates title</div>
    <div class="right-fill' border-cyan-800 border-2">Right fill</div>
    <div class="bot-left-corner border-cyan-800 border-2">Bot left corner</div>
    <div class="impact border-cyan-800 border-2">IMPACT</div>
    <div class="next_dates border-cyan-800 border-2">Next Dates</div>
    <div class="bot-right-corner border-cyan-800 border-2">
      Bot right corner
    </div>
    <div class="bot-left-fill border-cyan-800 border-2">Bot left fill</div>
    <div class="bot-right-fill border-cyan-800 border-2">Bot right fill</div>
  </div>
</template>

<style scoped>
.grid-areas {
  grid-template-areas:
    'top-left-corner    top-fill        top-fill        top-mid-fill    top-right-corner    top-right-corner'
    'left-fill          impro           impro           mid-fill        dates-title         right-fill'
    'bot-left-corner    impact          impact          impact          next_dates          bot-right-corner'
    'bot-left-corner    bot-left-fill   bot-left-fill   bot-left-fill   bot-right-fill      bot-right-corner';
}

.top-left-corner {
  grid-area: top-left-corner;
}

.top-fill {
  grid-area: top-fill;
}

.top-mid-fill {
  grid-area: top-mid-fill;
}

.top-right-corner {
  grid-area: top-right-corner;
}

.left-fill {
  grid-area: left-fill;
}

.impro {
  grid-area: impro;
}

.mid-fill {
  grid-area: mid-fill;
}

.dates-title {
  grid-area: dates-title;
}

.right-fill {
  grid-area: right-fill;
}

.bot-left-corner {
  grid-area: bot-left-corner;
}

.impact {
  grid-area: impact;
}

.next_dates {
  grid-area: next_dates;
}

.bot-right-corner {
  grid-area: bot-right-corner;
}

.bot-left-fill {
  grid-area: bot-left-fill;
}

.bot-right-fill {
  grid-area: bot-right-fill;
}
</style>
