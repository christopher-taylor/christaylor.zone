<script>
  import Job from "./Components/job.svelte";
  import Section from "./Components/section.svelte";
</script>

<header class="container">
  <div class="row">
    <h3 class="column">christaylor dot zone</h3>
  </div>
  <nav class="row">
    <div class="column">
      <a href="https://github.com/christopher-taylor">github</a>
      <a href="https://www.lightningstrikesthrice.com/">podcast</a>
      <a href="mailto:me@christaylor.zone">contact</a>
      <a href="javascript:if(window.print)window.print()">print me</a>
    </div>
  </nav>
  <hr />
</header>

<main class="container style-1">
  <div class="print-only row">
    <div class="column">
      <h3>Chris Taylor</h3>
      <h5>Full Stack Developer</h5>
    </div>
    <div class="column text-right">
      <p>206-922-9069</p>
      <p>me@christaylor.zone</p>
      <p>https://github.com/christopher-taylor</p>
    </div>
  </div>
    <Section heading="Experience">
    <Job title="Cloud Developer">
      <ul>
        <li>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </li>
        <li>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </li>
        <li>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </li>
      </ul>
    </Job>
    <Job title="Full-Stack Developer">
      <ul>
        <li>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </li>
        <li>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </li>
        <li>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </li>
      </ul>
    </Job>
    <Job title="Junior Front End Developer">
      <ul>
        <li>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </li>
        <li>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </li>
        <li>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </li>
      </ul>
    </Job>
  </Section>
  <Section heading="Education">
    <p class="mb-0"><b>Seattle Community College</b>, Seattle, WA</p>
    <p>Associates in Information Technology</p>
    <br class="print-only" />
    <p class="mb-0"><b>Udacity</b>, Seattle, WA<br /></p>
    <p>Front End Developer Nanodegree</p>
  </Section>
</main>

<footer class="container">
  <hr class="mb-0" />
  <div class="row">
    <div class="column text-center">
      <p class="mb-0">
        Made by me, Chris Taylor, using <a href="https://svelte.dev">Svelte</a>
        and <a href="https://milligram.io/">Milligram</a>.
      </p>
      <p class="mb-0">
        Code <a href="https://github.com/christopher-taylor/christaylor.zone"
          >here.</a
        >
      </p>
    </div>
  </div>
</footer>
