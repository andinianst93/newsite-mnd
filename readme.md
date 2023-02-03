index.html (homepage)

========
Heading 1

before: <h1 class="reTit1">Trading Forex, Saham, Minyak & Emas di HSB</h1>
after: <h1 class="reTit1">Trading Forex, Saham, Minyak & Emas</h1>
reasons: redundant because HSB already in the logo.

========

Button for mobile and desktop (I haven't changed it) 
before:  <div class="pc">
          <div class="flex1">
            <a
              class="pcbtn pcbtn2"
              href="https://ui.hsb.co.id/#/register/RVf"
              target="_blank"
              >Buka Akun Demo</a
            >
            <a
              class="pcbtn mouse"
              href="https://ui.hsb.co.id/#/register/RVf"
              target="_blank"
              >Buka Akun Live</a
            >
          </div>
        </div>
after: <div>
    <div class="pc">
        <a href='https://ui.hsb.co.id/#/register/RVf' class='pcbtn pcbtn2'> 
            <button type="button">Buka Akun Demo</button>
        </a>
        <a href='https://ui.hsb.co.id/#/register/RVf'  class="pcbtn mouse">
            <button type="button">Buka Akun Live</button>
        </a>
    </div>
</div>
example: https://prnt.sc/vnfpoTah7FQ5
reasons: Since it is a button it should be <button>. Also, the padding y inside the button could you make it center. Like this: https://prnt.sc/vnfpoTah7FQ5

========
Spread

Before: <li>
            <div class="numName alignR">Spreads<br/> mulai dari</div>
            <div class="numVal"><span>0,5</span><span class="pip">/pip</span></div>
          </li>
After:  <li>
            <div class="numName alignR">Spreads<br/> mulai dari</div>
            <div class="numVal"><span>0,14</span><span class="pip">/pip</span></div>
          </li>
reason: I confirmed it with Hendi (BD), he said that spreads is 0,14.

========

More about

Before: <a href="" class="more">More about Forex</a> /// including in Komoditas, Indeks, and Saham

After:  <a href="" class="more">More about Forex</a>
        <a href="" class="more">More about Komoditas</a>
        <a href="" class="more">More about Indeks</a>
        <a href="" class="more">More about Saham</a>
    

