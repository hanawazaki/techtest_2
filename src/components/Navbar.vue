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
      <li class="register">
        <a href="#">Register</a>
      </li>
      <li class="search">
        <a href="#">
          <img src="../assets/img/search.png" alt="" />
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
      &.menu {
        margin: 0 10px;
        padding: 0.5rem 1.5rem;
        &:hover {
          background-color: #e0e2e2;
          border-radius: 30px;
          padding: 0.5rem 1.5rem;
        }
      }
      &.active {
        background-color: #e0e2e2;
        border-radius: 30px;
        padding: 0.5rem 1.5rem;
      }

      a {
        text-decoration: none;
        color: #000;
      }
      &.register {
        margin-left: 2rem;
        margin-right: 1.25rem;
      }
      &.search {
        margin: 0 1.25rem;
        img {
          width: 1.25rem;
        }
      }
    }
  }
}
</style>