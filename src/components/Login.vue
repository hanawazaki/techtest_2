<template>
  <section class="login">
    <h1>
      Please log in to start using <br />
      <span>Booked Tool </span>
    </h1>
    <input type="email" placeholder="Email" size="35" />
    <input type="password" placeholder="Password" size="35" />
    <a class="login-button">Login</a>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss">
.login {
  background-color: #e2e3e4;
  display: flex;
  padding: 50px;
  color: #353638;
  justify-content: center;
  h1 {
    font-size: 1rem;
    font-weight: 500;
    margin-left: 2rem;
    margin-right: 2rem;

    span {
      font-weight: 700;
      font-size: 1.75rem;
      color: #1c1c1d;
    }
  }
  input {
    // height: 54px;
    border: none;
    border-radius: 6px;
    margin-right: 26px;
    margin-top: 10px;
  }

  .login-button {
    padding: 1.25rem 1.75rem;
    color: white;
    background-color: #468fcc;
    border-radius: 0.75rem;
    font-weight: 500;
    text-decoration: none;
    margin-top: 10px;
  }
}
</style>