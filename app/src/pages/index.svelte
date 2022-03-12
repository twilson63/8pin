<script>
  import NavBar from "../components/navbar.svelte";
</script>

<a id="home" />
<NavBar />
<main class="hero min-h-screen bg-base-200">
  <div class="hero-content text-center">
    <div class="max-w-md">
      <h1 class="text-5xl font-bold">8 pin</h1>
      <p class="py-6">Capture your moment!</p>
      <button class="btn btn-primary">Get Started</button>
    </div>
  </div>
</main>
<div class="hero min-h-screen bg-base-200">
  <div class="flex flex-row mx-24">
    <div class="w-1/2 mr-8">
      <a id="how"><h1 class="text-5xl font-bold">How it works</h1></a>
      <p class="mt-8">
        8pin uses the solana network to empower users to submit their moments to
        the permaweb. The permaweb is a permanent internet, which means what
        ever you store on the permaweb is forever.
      </p>
      <p class="mt-4">
        When you create a post with 8pin, instead of storing the post in a
        centralized database, 8pin publishes your post on the permaweb. The
        permaweb is accessible by everyone, and the data posted on the permaweb,
        can never be deleted, it is there forever.
      </p>
      <div class="mt-8">
        <a
          class="rounded bg-purple-600 text-white px-4 py-2"
          href="#getting-started">Getting Started</a
        >
      </div>
      <p class="py-6"><a href="#home" class="underline">Return</a></p>
    </div>
    <div>
      <img src="https://via.placeholder.com/600" alt="picture" />
    </div>
  </div>
</div>
<div class="hero min-h-screen bg-base-200">
  <div class="flex flex-row mx-24">
    <div>
      <img src="https://via.placeholder.com/600" alt="picture" />
    </div>
    <div class="w-1/2 ml-8">
      <a id="getting-started"
        ><h1 class="text-5xl font-bold">Getting Started</h1></a
      >
      <h3 class="mt-8 text-2xl">Prerequisites</h3>
      <p class="mt-8">
        * Phantom Wallet - <a class="underline" href="https://phantom.app/"
          >https://phantom.app/</a
        >
      </p>
      <p class="mt-4">* SOL - Load your wallet with a few dollars of SOL.</p>
      <p class="mt-4">In your phantom app, go to 8pin.com</p>
      <p class="mt-4">
        When you create a post with 8pin, instead of storing the post in a
        centralized database, 8pin publishes your post on the permaweb. The
        permaweb is accessible by everyone, and the data posted on the permaweb,
        can never be deleted, it is there forever.
      </p>
      <div class="mt-8">
        <a
          class="rounded bg-purple-600 text-white px-4 py-2"
          href="#getting-started">Getting Started</a
        >
      </div>
      <p class="py-6"><a href="#home" class="underline">Return</a></p>
    </div>
  </div>
</div>
