<template>
  <header>
    <div class="logo">
      <img src="../assets/img/logo.png" alt="logo_img" />
    </div>
    <ul>
      <li class="menu active">
        <a href="#">Home</a>
      </li>
      <li
        class="
          menu
          hover:bg-greyblueHover
          px-6
          py-2
          rounded-full
          transition
          duration-300
        "
      >
        <a href="#" class="">Discover</a>
      </li>
      <li class="ml-8 mr-5">
        <a href="#">Register</a>
      </li>
      <li class="mx-5">
        <a href="#">
          <img src="../assets/img/search.png" class="search" alt="" />
        </a>
      </li>
    </ul>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss">
header {
  display: flex;
  justify-content: space-between;
  margin: 0 1.75rem;

  .logo {
    img {
      width: 4rem;
    }
  }

  ul {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    li {
      list-style: none;
      a {
        text-decoration: none;
      }
      .active {
        background-color: #e0e2e2;
        border-radius: 30px;
        padding: 1.5rem 0.5rem;
      }

      .menu {
        margin: 0 10px;
      }
    }

    .search {
      width: 1.25rem;
    }
  }
}
</style>