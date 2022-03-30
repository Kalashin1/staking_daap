<template>
  <div class="bg-black text-yellow-100 m-8 rounded-md p-4 border-2 border-white">
    <div class="flex font-bold text-md sm:text-lg my-6 justify-between">
      <div class="space-y-4">
        <h5>Daily Profit</h5>
        <p>...%</p>
      </div>
      <div class="space-y-4">
        <h5>Total Return</h5>
        <p>...%</p>
        
      </div>
    </div>
    <div class="flex font-bold text-md sm:text-lg my-8 justify-between">
      <div class="space-y-4">
        <h5>Withdrawal Time</h5>
        <p>Time</p>
      </div>
      <div class="space-y-4">
        <h5>Staking Period</h5>
        <p>Days</p>
      </div>
    </div>
    <div class="flex font-bold text-md sm:text-lg my-8 justify-between">
      <div class="space-y-4 w-2/4">
        <h5>Enter Amount</h5>
        <p><input type="text" class="w-3/4 focus:outline-none focus:border-0 px-2 rounded-md py-2 bg-yellow-500" /></p>
      </div>
      <div class="space-y-4">
        <h5>18 Days Staking</h5>
        <p>...%</p>
      </div>
    </div>
    <div class="flex justify-center items-center">
      <button class="bg-yellow-400 shadow-md hover:border-white transition hover:bg-purple-900 font-bold rounded-md py-4 px-12 text-black">Stake Token</button>
    </div>
  </div>
</template>