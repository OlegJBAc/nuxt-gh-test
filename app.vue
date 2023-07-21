<template>
  <div>
    <NuxtLayout>
      <nav>
        <ul>
          <NuxtLink to="/">
            <li>
              <span>index page</span>
            </li>
          </NuxtLink >
          <NuxtLink to="about">
            <li>
              <span>about page</span>
            </li>
          </NuxtLink>

        </ul>
      </nav>
      <NuxtPage/>
    </NuxtLayout>
  </div>
</template>
