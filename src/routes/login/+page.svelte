<!-- LoginForm.svelte -->
<script>
  let username = "";
  let password = "";

  function handleSubmit() {
    // event.preventDefault();
    console.log("Username:", username);
    console.log("Password:", password);

}
</script>

<div class="flex flex-col justify-center my-10">
    <h1 class="text-center text-3xl font-semibold mb-5">One Album</h1>
    <p class="text-center mb-3 text-2xl font-semibold text-gray-500">Welcome, <br> Login to your Account</p>
    <form class="max-w-md mx-auto border border-gray-300 p-8 shadow-lg rounded" on:submit={handleSubmit}>
      <div class="mb-4">
        <label for="username" class="block text-gray-700 text-sm font-bold mb-2">Username</label>
        <input type="text" id="username" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" bind:value={username} placeholder="Enter your username" required>
      </div>
      <div class="mb-6">
        <label for="password" class="block text-gray-700 text-sm font-bold mb-2">Password</label>
        <input type="password" id="password" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" bind:value={password} placeholder="Enter your password" required>
      </div>
      <div class="flex items-center justify-center">
        <button type="submit" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline">
          Log In
        </button>
      </div>
    </form>
</div>
