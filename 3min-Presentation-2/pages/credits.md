---
layout: default
---

<div class="credits-box">
  <div class="credits-scroll">
    <h1>Project Neo Statistics*:</h1>
    <span style="font-size:8pt">*These are approximations without any claim for correctness.</span>
    <table class="stats-table">
      <tbody>
        <tr>
          <td class="td-num">1.5</td>
          <td class="td-text">Teas per Meeting</td>
        </tr>
        <tr>
          <td class="td-num">0.75</td>
          <td class="td-text">Trips to Cafeteria per Day</td>
        </tr>
        <tr>
          <td class="td-num">3</td>
          <td class="td-text">Jans Muffins</td>
        </tr>
        <tr>
          <td class="td-num">2</td>
          <td class="td-text">Sidequests</td>
        </tr>
        <tr>
          <td class="td-num">1</td>
          <td class="td-text">Meeting with Katja</td>
        </tr>
        <tr>
          <td class="td-num">6</td>
          <td class="td-text">Marko Lectures</td>
        </tr>
        <tr>
          <td class="td-num">42</td>
          <td class="td-text">Jonas Ted Talks</td>
        </tr>
        <tr>
          <td class="td-num">?</td>
          <td class="td-text">LLM Hallucinations</td>
        </tr>
        <tr>
          <td class="td-num">1</td>
          <td class="td-text">Physics Defining Solutions</td>
        </tr>
        <tr>
          <td class="td-num">😢</td>
          <td class="td-text">Faulty OCP Formulations</td>
        </tr>
      </tbody>
    </table>
    <div class="h-70"/>
    <h1>The docker was modified <code>18</code> times during this period!</h1>
  </div>
</div>

<style>
.stats-table {
  margin: 0 auto;
  width: 40%;
}

.stats-table td {
  padding: 0.5em 1em;
}

.td-num {
  text-align: right;
}

.td-text {
  text-align: left;
  font-weight: 500;
}

.credits-box {
  position: absolute;
  inset: 0;
  overflow: hidden;
}

.credits-scroll {
  position: absolute;
  left: 0;
  right: 0;
  text-align: center;
  animation: scrollUp 25s linear forwards;
}

@keyframes scrollUp {
  0%   { top: 100%; opacity: 1; }
  90%  { opacity: 1; }
  100% { top: -120%; opacity: 0; }
}
</style>
