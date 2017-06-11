---
layout: default
title: Bitcoin Minería Preguntas Frecuentes
description: Bitcoin Minería Preguntas Frecuentes
---

<h2>Table of contents</h2>

<ul>
  <li><a href="#what-is-bitcoin-mining">¿Qué es la minería de Bitcoin?</a></li>
  <li><a href="#how-does-bitcoin-mining-work">¿Cómo funciona la minería de Bitcoins?</a></li>
  <li><a href="#isnt-bitcoin-mining-a-waste-of-energy">¿Es la minería de Bitcoins una pérdida de tiempo?</a></li>
  <li><a href="#how-does-mining-help-secure-bitcoin">¿Cómo ayuda la minería a proteger Bitcoin?</a></li>
  <li><a href="#what-do-i-need-to-start-mining">¿Qué necesito para comenzar con la minería?</a></li>
  <li><a href="#what-does-mhs-ghs-mean">¿Qué significan MH/s y GH/s?</a></li>
  <li><a href="#what-does-wgh-mean">¿Qué significa W/Gh?</a></li>
  <li><a href="#calculate-bitcoin-mining-profitability">¿Cómo calculo mi ganancia de minería de Bitcoins?</a></li>
  <li><a href="#what-does-hashing-mean">¿Qué significa hashing?</a></li>
  <li><a href="#bitcoin-mining-pool">¿Qué es un pool de minería de Bitcoin?</a></li>
  <li><a href="#what-does-GPU-stand-for">¿Para qué se establece un GPU?</a></li>
  <li><a href="#bitcoin-mining-share">¿Qué es una cuota de minería de Bitcoin?</a></li>
  <li><a href="#bitcoin-mining-module">¿Qué es un módulo de minería de Bitcoin?</a></li>
  <li><a href="#what-does-ASIC-stand-for">¿Para qué se establece ASIC?</a></li>
  <li><a href="#what-does-FPGA-stand-for">¿Para qué se establece el FPGA?</a></li>
  <li><a href="#data">¿Dónde puedo ver los datos de minería de cada bloque?</a></li>
</ul>

<h3 id="what-is-bitcoin-mining">¿Qué es la minería de Bitcoin?</h3>

<img src="/images/icons/mining.png" class="pull-left bitcoin-icon">

<p>La minería es el proceso de utilizar poder computacional para procesar transacciones, asegurar la red, y mantener a todos en la red sincronizados juntos. Puede ser percivido como un centro de datos de Bitcoin, exepto porque gue diseñado para ser totalmente descentralizado, con mineros operando en todos los países y ningún individuo teniendo el control de la red. </p>

<p>Este proceso se conoce como "minería" como una analogía de la minería del oro, debido a que también es un mecanismo temporal para emitir nuevos bitcoins. A diferencia de la minería del oro, sin embargo, la minería de Bitcoin provee una recompensa a cambio de servicios útiles requeridas para operar una red segura de pagos. La Minería aún será necesaria cuando el último bitcoin sea creado.</p>

<h3 id="how-does-bitcoin-mining-work">¿Cómo funciona la minería de Bitcoins?</h3>
<p>Cualquiera puede convertirse en un minero de Bitcoin, ejecutando un software y módulos de Bitcoin con <a href="/bitcoin-mining-hardware/">hardware especializado en minería de Bitcoin</a>. El software de minería escucha las transmisiones de transacciones a través de la red peer-to-peer (de par a par), y realiza las tareas apropiadas para procesar y confirmar estas transacciones. Los mineros de Bitcoin realizan este trabajo porque pueden ganar honorarios de la transacción, pagados por los usuarios para un procesamiento más rápido de la transacción, y los bitcoins recién creados publicados en existencia según una fórmula fija.</p>

<p>Para que las nuevas transacciones sean confirmadas, deben ser incluidas en un bloque junto con <a href="/what-is-proof-of-work/">una prueba matemática de trabajo</a>. Estas pruebas son muy difíciles de generar porque no hay forma de crearlas aparte de intentar miles de millones de cálculos por segundo. Esto requiere que los mineros realicen estos cálculos antes de que sus bloques sean aceptados por la red y antes de que sean recompensados. A medida que más personas comienzan a minar, la dificultad de encontrar bloques válidos es aumentada automáticamente por la red para asegurar que el tiempo promedio para encontrar un bloque permanezca igual a 10 minutos. Como resultado, la minería es un negocio muy competitivo donde ningún minero individual puede controlar lo que está incluido en la cadena de bloque.</p>

<p>El video de abajo de una granja minera Bitcoin en China le dará una mejor idea de lo competitiva que se ha convertido la minería Bitcoin:</p>

<iframe width="740" height="360" src="https://www.youtube.com/embed/K8kua5B5K3I?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

<p>La prueba de trabajo también está diseñada para depender del bloque anterior para forzar un orden cronológico en la cadena de bloques. Esto hace que sea exponencialmente difícil invertir las transacciones anteriores porque esto requiere el recálculo de las pruebas de trabajo de todos los bloques subsiguientes. Cuando dos bloques se encuentran al mismo tiempo, los mineros trabajan en el primer bloque que reciben y cambian a la cadena más larga de bloques tan pronto como se encuentra el siguiente bloque. Esto permite a la minería asegurar y mantener un consenso global basado en el poder de procesamiento.</p>
<p>Los mineros de Bitcoin no pueden engañar aumentando su propia recompensa ni procesar transacciones fraudulentas que pudieran corromper la red de Bitcoin porque todos los nodos de Bitcoin rechazan cualquier bloque que contenga datos no válidos según las reglas del protocolo Bitcoin. En consecuencia, la red permanece segura incluso si no se puede confiar en todos los mineros de Bitcoin.</p>

<h3 id="isnt-bitcoin-mining-a-waste-of-energy">¿Es la minería de Bitcoins una pérdida de tiempo?</h3>
<p>El gasto de energía para asegurar y operar un sistema de pago no es un desperdicio. Como cualquier otro servicio de pago, el uso de Bitcoins implica costos de procesamiento. Los servicios necesarios para el funcionamiento de los sistemas monetarios actualmente extendidos como los bancos, las tarjetas de crédito y los vehículos blindados, también utilizan mucha energía. Aunque a diferencia del Bitcoin, su consumo total de energía no es transparente y no puede medirse tan fácilmente. La tasa de hash total de la red de Bitcoin está <a href="https://bitcoinwisdom.com/bitcoin/difficulty">públicamente disponible</a> y puede ser utilizada para estimar los costos totales de electricidad de la red.</p>

<img src="/images/hashrate.png" />

<p>La minería Bitcoin ha sido diseñada para ser más optimizada con el tiempo, con el hardware especializado que consume menos energía, y los costos operativos de la minería deben seguir siendo proporcionales a la demanda. Cuando la minería Bitcoin se vuelve demasiado competitiva y menos rentable, algunos mineros optan por detener sus actividades. Además, toda la energía gastada en energía se transforma finalmente en calor, y los mineros más rentables serán aquellos que han puesto este calor en buen uso. Algunos mineros, por ejemplo, [utilizan el calor generado por los mineros bitcoin para complementar sistemas de calefacción regulares](http://www.waters.nyc/writing/325). </p>

<p>Una red de minería óptimamente eficiente es aquella que no está consumiendo realmente ninguna energía adicional. Si bien esto es un ideal, la economía de la minería es tal que los mineros se esfuerzan individualmente para alcanzarla.</p>

<h3 id="how-does-mining-help-secure-bitcoin">¿Cómo ayuda la minería a proteger Bitcoin?</h3>
<p>La minería crea el equivalente a una lotería competitiva que hace muy difícil para cualquiera agregar consecutivamente nuevos bloques de transacciones a la cadena de bloques. Esto protege la neutralidad de la red impidiendo que cualquier individuo obtenga el poder de bloquear ciertas transacciones. Esto también evita que cualquier individuo reemplace partes de la cadena de bloque para revertir sus propios gastos, lo que podría ser utilizado para defraudar a otros usuarios. La minería hace que sea exponencialmente más difícil revertir una transacción anterior requiriendo la reescritura de todos los bloques que ocurrieron después de la transacción objetivo.</p>

<h3 id="what-do-i-need-to-start-mining">¿Qué necesito para comenzar con la minería?</h3>
<p>En los primeros días del Bitcoin, cualquiera podía encontrar un nuevo bloque utilizando la CPU de su computadora. A medida que más y más personas empezaron a minar, la dificultad de encontrar nuevos bloques aumentó en gran medida hasta el punto en que el único método rentable de minería hoy en día es utilizando sistemas especializados de<a href="https://www.hobbymining.com/mining-hardware/">hardware</a>.</p>

<h3 id="what-does-mhs-ghs-mean">What does MH/s, GH/s mean?</h3>
<p>These abbreviations stand for the hashing power that your miner is generating. MH/s stands for <i>megahash per second</i> and GH/s stands for <i>gigahash per second</i>. There is a direct correlation between how fast your miner works and how profitable it will be. </p>

<h3 id="what-does-wgh-mean">What does W/Gh and W/Th mean?</h3>
<p>W/Gh and W/Th are abbreviations for <i>watts per gigahash</i> and <i>watts per terahash</i>. These metrics calculate how many hashes a miner can run per watt of electricity. Mining hardware with lower W/Gh and W/Th are more efficient. Currently, the <a href="http://geni.us/37CM">Antminer S7</a> and <a href="http://geni.us/3upk">Avalon6</a> are the most efficient miners available for purchase, at  0.25 W/Gh  and  0.29 W/Gh, respectively.</p>

<h3 id="calculate-bitcoin-mining-profitability">How do I calculate my Bitcoin mining profitability?</h3>
<p>You can use <a href="https://alloscomp.com/bitcoin/calculator">bitcoin mining profitability calculators</a> to calculate the <a href="/bitcoin-mining-profitability/">profitability of mining</a> under varying circumstances, to include difficulty increases, power consumption, and average hashrate, for example.</p>

<h3 id="what-does-hashing-mean">What does hashing mean?</h3>
<p>The term "hashing" means how quickly your hardware is processing data from the Blockchain and solving the complex mathematical equations that are required to earn bitcoins.</p>

<h3 id="bitcoin-mining-pool">What is a Bitcoin mining pool?</h3>
<p>A <a href="/bitcoin-mining-pools/">mining pool is a group of miners</a> who have shared their hashing resources to solve blocks together and the rewards are then distributed amongst the members.</p>

<p>Let's say Bob runs a Bitcoin mining farm with 1% of the Bitcoin network hash rate. His machines only find, on average, one out of every 100 blocks. Bob becomes impatient and wants more frequent payouts. He joins a mining pool with 20% of the network hash rate. Instead of getting paid on average once per 100 blocks, Bob now receives smaller but more frequent payouts every five blocks.</p>

<h3 id="what-does-GPU-stand-for">What does GPU stand for?</h3>
<p>A Graphics Processing Unit powers most computer video cards and can be used to mine Bitcoins.</p>

<h3 id="bitcoin-mining-share">What is a Bitcoin mining share?</h3>
<p>A share is merely an accounting method to keep the miners honest and fairly divide any rewards earned by the pool.</p>

<h3 id="bitcoin-mining-module">What is a Bitcoin mining module?</h3>
<p>A Bitcoin mining module is usually a worker as assigned in the Bitcoin mining software. For example, four GPUs are plugged into the motherboard constituting the Bitcoin mining hardware. Then the Bitcoin mining software identifies each GPU as a unique worker. So, this small Bitcoin mining rig would be composed for four Bitcoin mining modules.</p>

<h3 id="what-does-ASIC-stand-for">What does ASIC stand for?</h3>
<p>An Application-Specific Integrated Circuit is a special chip designed specifically for mining Bitcoin and is much more energy-efficient and faster than GPU or FPGA mining.</p>

<h3 id="what-does-FPGA-stand-for">What does FPGA stand for?</h3>
<p>A Field-Progammable Gate Array was already an established hardware product that can be used for different purposes, but in this case the technology was repurposed for mining Bitcoin.</p>

<h3 id="data">Where can I view mining data about each block?</h3>
<p>The mining rewards and transaction fees for each block can be viewed online with any block explorer.</p>

<img src="/images/blockinfo.png" />

<p>In the example above, we get information on block <a href="https://blockchain.info/block/00000000000000000459fd9e1ee16c2f10a834bdc5c1b5fd2f1a4485063c8e18">#408450</a>:</p>

<ul>
<li><b>Number of transactions:</b> Block #408450 contained 185 transactions.</li>
<li><b>Transaction fees:</b> There were 0.05502059 BTC worth of transaction fees in block #408450. The miner or mining pool (explained below) that mined this block receives the entirety of these fees.</li>
<li><b>Height:</b> Height is another name for block number. The first block mined was <a href="https://blockchain.info/block/00000000839a8e6886ab5951d76f411475428afc90947ee320161bbf18eb6048">block #1</a> and is called the <a href="https://en.bitcoin.it/wiki/Genesis_block">Genesis block</a>. </li>
<li><b>Relayed By:</b> This block was successfully solved by <a href="https://antpool.com/home.htm">Antpool</a>, which is a <a href="/bitcoin-mining-pools/">Bitcoin mining pool</a>. </li>
<li><b>Block Reward:</b> This block contained a 25 BTC reward, which is fully rewarded to the miner that relayed the block--in this case Antpool.</li> 

</ul>
