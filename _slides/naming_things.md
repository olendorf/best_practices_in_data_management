---

order: 120

---

<h2>Naming Things</h2>

<div>
  <div class="small two-col left fragment">
    <h3>Temperature</h3>
    <ul>
        <li class="no">
            t
            <ul><li>What the heck is t?</li></ul>
        </li>
        <li class="caution fragment">
            temp
            <ul><li>Temporary or Temperature?</li></ul>
        </li>
        <li class="ok fragment">
            temperature
            <ul><li>Pretty good!</li></ul>
        </li>
        <li class="best fragment">
            temperature_celsius
            <ul><li>Adding units reduces documentation</li></ul>
        </li>
    </ul>
  </div>
  
  <div class="small two-col right fragment">
    <h3>Working With Dates</h3>
    <ul class="smallest">
        <li class="no">
            image_120702
            <ul><li>December, July or February?</li></ul>
        </li>
        <li class="ok fragment">
            image_20120702
            <ul><li>Good if following <a href="https://en.wikipedia.org/wiki/ISO_8601">ISO 8601 (YYYYMMDD)</a></li></ul>
        </li>
        <li class="ok fragment">
            image_july_02_2012
            <ul><li>Unambiguous</li></ul>
        </li>
        <li class="ok fragment">
            image_1341235788
            <ul>
                <li>Seconds since January 1, 1970 00:00:00</li>
                <li>Precision to seconds</li>
                <li>Easy for computers to understand</li>
                <li>Hard for humans to understand</li>
            </ul>
        </li>
        
    </ul>
  </div>
</div>
<hr/>
<div>
    <pre>There are two hard things in computer science: cache invalidation
    and naming things.
    
    -- Phil Karlton</pre>
</div>








