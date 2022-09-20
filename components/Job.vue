<template>
  <section
    class="container-md mx-4 p-2 d-flex justify-content-between border rounded"
  >
    <div>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="16"
        height="16"
        fill="currentColor"
        class="bi bi-check-circle"
        viewBox="0 0 16 16"
      >
        <path
          d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"
        />
        <path
          d="M10.97 4.97a.235.235 0 0 0-.02.022L7.477 9.417 5.384 7.323a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-1.071-1.05z"
        />
      </svg>
    </div>
    <div class="border round" style="height: 150px" />
    <article>
      <h2>VM Name</h2>
      <ul>
        <li>vCPUs: 4</li>
        <li>RAM: 8192</li>
        <li>NET: halam1</li>
        <li>VOL: 9</li>
      </ul>
    </article>
    <div class="border round" style="height: 150px" />
    <article>
      <p>192.168.50.120</p>
      <p>7/8 Snapshots</p>
      <b-progress :value="value" :max="max" class="mb-3"></b-progress>
      <p>sending snapshot...</p>
      <p>7/8 Snapshots</p>
    </article>
    <div class="border round" style="height: 150px" />
    <article>
      <h2>DR-ID 454</h2>
      <ul>
        <li>Round: 390</li>
        <li>Erros: 0</li>
      </ul>
      <button type="button">LOG</button>
    </article>
    <div class="border round" style="height: 150px" />
    <article>
      <button>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="20"
          height="20"
          fill="currentColor"
          class="bi bi-pencil"
          viewBox="0 0 16 16"
        >
          <path
            d="M12.146.146a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-10 10a.5.5 0 0 1-.168.11l-5 2a.5.5 0 0 1-.65-.65l2-5a.5.5 0 0 1 .11-.168l10-10zM11.207 2.5 13.5 4.793 14.793 3.5 12.5 1.207 11.207 2.5zm1.586 3L10.5 3.207 4 9.707V10h.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.5h.293l6.5-6.5zm-9.761 5.175-.106.106-1.528 3.821 3.821-1.528.106-.106A.5.5 0 0 1 5 12.5V12h-.5a.5.5 0 0 1-.5-.5V11h-.5a.5.5 0 0 1-.468-.325z"
          />
        </svg></button
      ><button>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="20"
          height="20"
          fill="currentColor"
          class="bi bi-x-lg"
          viewBox="0 0 16 16"
        >
          <path
            d="M2.146 2.854a.5.5 0 1 1 .708-.708L8 7.293l5.146-5.147a.5.5 0 0 1 .708.708L8.707 8l5.147 5.146a.5.5 0 0 1-.708.708L8 8.707l-5.146 5.147a.5.5 0 0 1-.708-.708L7.293 8 2.146 2.854Z"
          />
        </svg>
      </button>
    </article>
  </section>
</template>

<script></script>
