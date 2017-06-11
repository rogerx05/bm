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
  <li><a href="#how-does-mining-help-secure-bitcoin">¿Cómo hace la minería más seguro al Bitcoin?</a></li>
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

<p>For new transactions to be confirmed, they need to be included in a block along with a <a href="/what-is-proof-of-work/">mathematical proof of work</a>. Such proofs are very hard to generate because there is no way to create them other than by trying billions of calculations per second. This requires miners to perform these calculations before their blocks are accepted by the network and before they are rewarded. As more people start to mine, the difficulty of finding valid blocks is automatically increased by the network to ensure that the average time to find a block remains equal to 10 minutes. As a result, mining is a very competitive business where no individual miner can control what is included in the block chain.</p>

<p>The video below of a Bitcoin mining farm in China will give you a better idea of just how competitive Bitcoin mining has become:</p>

<iframe width="740" height="360" src="https://www.youtube.com/embed/K8kua5B5K3I?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

<p>The proof of work is also designed to depend on the previous block to force a chronological order in the block chain. This makes it exponentially difficult to reverse previous transactions because this requires the recalculation of the proofs of work of all the subsequent blocks. When two blocks are found at the same time, miners work on the first block they receive and switch to the longest chain of blocks as soon as the next block is found. This allows mining to secure and maintain a global consensus based on processing power.</p>
<p>Bitcoin miners are neither able to cheat by increasing their own reward nor process fraudulent transactions that could corrupt the Bitcoin network because all Bitcoin nodes would reject any block that contains invalid data as per the rules of the Bitcoin protocol. Consequently, the network remains secure even if not all Bitcoin miners can be trusted.</p>

<h3 id="isnt-bitcoin-mining-a-waste-of-energy">Isn't Bitcoin mining a waste of energy?</h3>
<p>Spending energy to secure and operate a payment system is hardly a waste. Like any other payment service, the use of Bitcoin entails processing costs. Services necessary for the operation of currently widespread monetary systems, such as banks, credit cards, and armored vehicles, also use a lot of energy. Although unlike Bitcoin, their total energy consumption is not transparent and cannot be as easily measured. The total Bitcoin network hash rate is <a href="https://bitcoinwisdom.com/bitcoin/difficulty">publicly available</a> and can be used to estimate the network's total electricity costs.</p>

<img src="/images/hashrate.png" />

<p>Bitcoin mining has been designed to become more optimized over time with specialized hardware consuming less energy, and the operating costs of mining should continue to be proportional to demand. When Bitcoin mining becomes too competitive and less profitable, some miners choose to stop their activities. Furthermore, all energy expended mining is eventually transformed into heat, and the most profitable miners will be those who have put this heat to good use. Some miners, for example, [use the heat generated by bitcoin miners to supplement regular heating systems](http://www.waters.nyc/writing/325). </p>

<p>An optimally efficient mining network is one that isn't actually consuming any extra energy. While this is an ideal, the economics of mining are such that miners individually strive toward it.</p>

<h3 id="how-does-mining-help-secure-bitcoin">How does mining help secure Bitcoin?</h3>
<p>Mining creates the equivalent of a competitive lottery that makes it very difficult for anyone to consecutively add new blocks of transactions into the block chain. This protects the neutrality of the network by preventing any individual from gaining the power to block certain transactions. This also prevents any individual from replacing parts of the block chain to roll back their own spends, which could be used to defraud other users. Mining makes it exponentially more difficult to reverse a past transaction by requiring the rewriting of all blocks that occurred after the target transaction.</p>

<h3 id="what-do-i-need-to-start-mining">What do I need to start mining?</h3>
<p>In the early days of Bitcoin, anyone could find a new block using their computer's CPU. As more and more people started mining, the difficulty of finding new blocks increased greatly to the point where the only cost-effective method of mining today is using specialized <a href="https://www.hobbymining.com/mining-hardware/">hardware</a>.</p>

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
