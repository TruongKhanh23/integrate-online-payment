<template>
  <footer class="footer has-cards">
    <div class="container">
      <hr />
      <div class="row align-items-center justify-content-md-between">
        <div class="col-md-6">
          <div class="copyright">
            &copy; {{ year }}
            <a
              href="https://www.creative-tim.com"
              target="_blank"
              rel="noopener"
              >Truong Khanh</a
            >
          </div>
        </div>
        <div class="col-md-6">
          <ul class="nav nav-footer justify-content-end">
            <li class="nav-item">
              <a
                href="https://khanhtn.online/"
                class="nav-link"
                target="_blank"
                rel="noopener"
                >Truong Khanh</a
              >
            </li>
            <li class="nav-item">
              <a
                href="https://khanhtn.online/about?lang=en"
                class="nav-link"
                target="_blank"
                rel="noopener"
                >About Me</a
              >
            </li>
            <li class="nav-item">
              <a
                href="https://khanhtn.online/projects?lang=en"
                class="nav-link"
                target="_blank"
                rel="noopener"
                >Projects</a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: "app-footer",
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style></style>
