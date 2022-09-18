
<div class="hidden space-x-8 sm:-my-px sm:ml-10 sm:flex">
    <BreezeNavLink :href="route('dashboard')" :active="route().current('dashboard')">Dashboard</BreezeNavLink>
    <BreezeNavLink :href="route('posts.index')" :active="route().current('posts.index')">Posts</BreezeNavLink>
  </div>
