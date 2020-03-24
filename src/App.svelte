<script>
  export let name;
</script>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<header>
  <h1>COMPANIES INCOME TABLE</h1>
</header>

<nav id="nav">
  <input type="text" id="input" placeholder="filter by name" value="" />
</nav>

<main>
  <table>
    <thead>
      <th>id</th>
      <th>city</th>
      <th>name</th>
      <th>total income</th>
    </thead>
    <tbody>
      <tr>
        <td>Loading...</td>
        <td />
        <td />
        <td />
      </tr>
    </tbody>
  </table>
</main>

<footer>1 2 3 4 5 ... pagination pages buttons</footer>

<div id="modal" class="modal">
  <div class="modal-content">
    <span id="closeBtn" class="closeBtn">&times;</span>
    <div id="modal-data" class="modal-data">Data to be loaded</div>
    <!-- <form id="range">
      from:
      <input type="month" name="start" value="2019-01" id="startDate" />
      to:
      <input type="month" name="end" value="2020-01" id="endDate" />
      <input type="submit" value="Submit form" />
    </form> -->
    <canvas id="myChart" />
  </div>
</div>

<!-- <script src="https://cdn.jsdelivr.net/npm/chart.js@2.9.3"></script> -->
