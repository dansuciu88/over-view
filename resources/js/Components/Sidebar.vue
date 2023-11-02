<template>
    <aside class="sidebar">
      <!-- Sidebar content here -->
      <nav>
        <ul>
          <li><inertia-link href="/dashboard">Dashboard</inertia-link></li>
          <li><inertia-link href="/profile">Profile</inertia-link></li>
          <!-- Add other links as needed -->
        </ul>
      </nav>
    </aside>
  </template>

  <script>
  export default {
    name: 'Sidebar',
  };
  </script>

  <style scoped>
  .sidebar {
    /* Your sidebar styles */
  }
  </style>
