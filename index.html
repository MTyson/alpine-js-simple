<html>
<head>
  <script src="https://unpkg.com/alpinejs@3.1.1/dist/cdn.min.js" defer></script>
  <script>
    async function getPresidents() {
      const response = await fetch('https://raw.githubusercontent.com/hitch17/sample-data/master/presidents.json');
      presidents = "foobar";//await response.json();
      //alert(presidents);
    }
    function foo(){
      this.presidents = ['bar'];
      presidents = 'bar';
    }
  </script>
</head>
<body>
  <div x-data="{
      filter: '',
      presidents: [],
      getPresidents: function(){
        return this.presidents.filter(pres => pres.president.includes(this.filter) )
      }
    }" 
    x-init="(
      async () => {
        const response = await fetch('https://raw.githubusercontent.com/hitch17/sample-data/master/presidents.json');
        presidents = await response.json();
      }
    )()">

    <input x-model="filter" />
    <span x-text="filter"></span>

    <ul>
      <template x-for="pres in getPresidents">
        <li><div x-text="pres.president" x-on:click="pres.show = ! pres.show"></div>
          <div x-show="pres.show" x-transition>
            From: <span x-text="pres.took_office"></span> Until: <span x-text="pres.left_office"></span></li>
          </div>
      </template>
    </ul>
    
    <span x-text="JSON.stringify(presidents)"></span>
  </div>
</body>
</html>