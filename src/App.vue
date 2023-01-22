<script setup>
import LikeSad from "./components/LikeSad.vue";
</script>

<template>
  <div>
    <section class="py-5">
      <div class="row py-lg-5">
        <h1 style="text-align: center">Album example</h1>
        <h4 style="text-align: center">
          Something short and leading about the collection below—its contents, the
          creator, etc. Make it short and sweet, but not too short so folks don’t simply
          skip over it entirely.
        </h4>
      </div>
    </section>
    <div class="album py-5 bg-light">
      <div class="container">
        <div class="card" style="background-color: rgb(255, 192, 192)">
          <img
            src="https://lh3.googleusercontent.com/ZdaBrzMx6-mpsnUKy6BvcBfSKuRF-JOkHG538PSdWY0aOjP2rOcL_nm_zqu0OIQYs03hRiUi820EofFEEUcmY_4DhUoqWiCP2tQjw7vyshWQg7WvsINw70nPrNgvKcTgcLYAY-Cv-x1BTg6xCgwycZ-DBPDi9zrkvu735o5pHgxyQA4-6PmOEsTCd-F9wjE_gi66O-mKiOZW6ediZpqno2h7hgJvDEpFnLdtx_rSduZbfj_9SUQ48WtzonLFMxBwSOm1Ge1wbx2c8o3BPVIDyOfhM9hE8LC31G1w7N2-XVKRcKSuO0ixrLEEwjJfb3z56ri6jaWN4wt--0YCw5EMEhvh1LyZl_ud8Oa6j7Bx8gRdReahR2rLEo_RusW41f_-UbheJCl8YT3cXcZIR6OcSvw7we4vTf05zx6X65Ta-EbVrB9q7zf7v2Pf6OpJHPOFp9DHjWOlqNhCdLVMFDYYBR8xz6AiyPMbEG0xhEsIGMoxgZSU5ACAkBP9TG01JSYMfOArultvMnjaTT9psg7sQeelMvwl6hSHUHDo7sPMjnMPBy2fa5bZkks8s0uQiwwkXclJxteaXciz9UQcwDzGwTICZlkdBUzpV6rdHAS9gI_txWkeHbMr9RFnfJnh2zWG-YTF__H7nildhZQtQxulGT9vr2V-6RKxYajXFQELOjtWftxvO5oZBUgpY5ohHAyp4kHgsANF7iG5hFY7E0L89fWoDr-KMnOJ_W0vsDfXDPWMvJ0FnP2SerYhyWuNvZaqXRsPLxatWEDYNJHnBCKcbC_HZjIwsc_ENqvYEnPF_c6uqeMxFH17zfrVZCJZ1iWxK0D4O_wwxuJxC4LbD1oVeJymd2R5IyH4A9ENlABbzJDRMWtYgxU69031HRVr6rczBZcnNFCw2qDw1tKBSJV9Wp5RPZHqy-ThO4x-Aq6xT8YIa5d9EDamAfYqk0nz0oc547FqAhlUF0qJBQITj0cE=s893-no?authuser=0"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the bulk of
              the card's content.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
        <div class="card" style="background-color: rgb(255, 224, 192)">
          <img
            src="https://lh3.googleusercontent.com/ZdaBrzMx6-mpsnUKy6BvcBfSKuRF-JOkHG538PSdWY0aOjP2rOcL_nm_zqu0OIQYs03hRiUi820EofFEEUcmY_4DhUoqWiCP2tQjw7vyshWQg7WvsINw70nPrNgvKcTgcLYAY-Cv-x1BTg6xCgwycZ-DBPDi9zrkvu735o5pHgxyQA4-6PmOEsTCd-F9wjE_gi66O-mKiOZW6ediZpqno2h7hgJvDEpFnLdtx_rSduZbfj_9SUQ48WtzonLFMxBwSOm1Ge1wbx2c8o3BPVIDyOfhM9hE8LC31G1w7N2-XVKRcKSuO0ixrLEEwjJfb3z56ri6jaWN4wt--0YCw5EMEhvh1LyZl_ud8Oa6j7Bx8gRdReahR2rLEo_RusW41f_-UbheJCl8YT3cXcZIR6OcSvw7we4vTf05zx6X65Ta-EbVrB9q7zf7v2Pf6OpJHPOFp9DHjWOlqNhCdLVMFDYYBR8xz6AiyPMbEG0xhEsIGMoxgZSU5ACAkBP9TG01JSYMfOArultvMnjaTT9psg7sQeelMvwl6hSHUHDo7sPMjnMPBy2fa5bZkks8s0uQiwwkXclJxteaXciz9UQcwDzGwTICZlkdBUzpV6rdHAS9gI_txWkeHbMr9RFnfJnh2zWG-YTF__H7nildhZQtQxulGT9vr2V-6RKxYajXFQELOjtWftxvO5oZBUgpY5ohHAyp4kHgsANF7iG5hFY7E0L89fWoDr-KMnOJ_W0vsDfXDPWMvJ0FnP2SerYhyWuNvZaqXRsPLxatWEDYNJHnBCKcbC_HZjIwsc_ENqvYEnPF_c6uqeMxFH17zfrVZCJZ1iWxK0D4O_wwxuJxC4LbD1oVeJymd2R5IyH4A9ENlABbzJDRMWtYgxU69031HRVr6rczBZcnNFCw2qDw1tKBSJV9Wp5RPZHqy-ThO4x-Aq6xT8YIa5d9EDamAfYqk0nz0oc547FqAhlUF0qJBQITj0cE=s893-no?authuser=0"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the bulk of
              the card's content.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
        <div class="card" style="background-color: rgb(255, 255, 192)">
          <img
            src="https://lh3.googleusercontent.com/ZdaBrzMx6-mpsnUKy6BvcBfSKuRF-JOkHG538PSdWY0aOjP2rOcL_nm_zqu0OIQYs03hRiUi820EofFEEUcmY_4DhUoqWiCP2tQjw7vyshWQg7WvsINw70nPrNgvKcTgcLYAY-Cv-x1BTg6xCgwycZ-DBPDi9zrkvu735o5pHgxyQA4-6PmOEsTCd-F9wjE_gi66O-mKiOZW6ediZpqno2h7hgJvDEpFnLdtx_rSduZbfj_9SUQ48WtzonLFMxBwSOm1Ge1wbx2c8o3BPVIDyOfhM9hE8LC31G1w7N2-XVKRcKSuO0ixrLEEwjJfb3z56ri6jaWN4wt--0YCw5EMEhvh1LyZl_ud8Oa6j7Bx8gRdReahR2rLEo_RusW41f_-UbheJCl8YT3cXcZIR6OcSvw7we4vTf05zx6X65Ta-EbVrB9q7zf7v2Pf6OpJHPOFp9DHjWOlqNhCdLVMFDYYBR8xz6AiyPMbEG0xhEsIGMoxgZSU5ACAkBP9TG01JSYMfOArultvMnjaTT9psg7sQeelMvwl6hSHUHDo7sPMjnMPBy2fa5bZkks8s0uQiwwkXclJxteaXciz9UQcwDzGwTICZlkdBUzpV6rdHAS9gI_txWkeHbMr9RFnfJnh2zWG-YTF__H7nildhZQtQxulGT9vr2V-6RKxYajXFQELOjtWftxvO5oZBUgpY5ohHAyp4kHgsANF7iG5hFY7E0L89fWoDr-KMnOJ_W0vsDfXDPWMvJ0FnP2SerYhyWuNvZaqXRsPLxatWEDYNJHnBCKcbC_HZjIwsc_ENqvYEnPF_c6uqeMxFH17zfrVZCJZ1iWxK0D4O_wwxuJxC4LbD1oVeJymd2R5IyH4A9ENlABbzJDRMWtYgxU69031HRVr6rczBZcnNFCw2qDw1tKBSJV9Wp5RPZHqy-ThO4x-Aq6xT8YIa5d9EDamAfYqk0nz0oc547FqAhlUF0qJBQITj0cE=s893-no?authuser=0"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the bulk of
              the card's content.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
        <div class="card" style="background-color: rgb(192, 255, 192)">
          <img
            src="https://lh3.googleusercontent.com/ZdaBrzMx6-mpsnUKy6BvcBfSKuRF-JOkHG538PSdWY0aOjP2rOcL_nm_zqu0OIQYs03hRiUi820EofFEEUcmY_4DhUoqWiCP2tQjw7vyshWQg7WvsINw70nPrNgvKcTgcLYAY-Cv-x1BTg6xCgwycZ-DBPDi9zrkvu735o5pHgxyQA4-6PmOEsTCd-F9wjE_gi66O-mKiOZW6ediZpqno2h7hgJvDEpFnLdtx_rSduZbfj_9SUQ48WtzonLFMxBwSOm1Ge1wbx2c8o3BPVIDyOfhM9hE8LC31G1w7N2-XVKRcKSuO0ixrLEEwjJfb3z56ri6jaWN4wt--0YCw5EMEhvh1LyZl_ud8Oa6j7Bx8gRdReahR2rLEo_RusW41f_-UbheJCl8YT3cXcZIR6OcSvw7we4vTf05zx6X65Ta-EbVrB9q7zf7v2Pf6OpJHPOFp9DHjWOlqNhCdLVMFDYYBR8xz6AiyPMbEG0xhEsIGMoxgZSU5ACAkBP9TG01JSYMfOArultvMnjaTT9psg7sQeelMvwl6hSHUHDo7sPMjnMPBy2fa5bZkks8s0uQiwwkXclJxteaXciz9UQcwDzGwTICZlkdBUzpV6rdHAS9gI_txWkeHbMr9RFnfJnh2zWG-YTF__H7nildhZQtQxulGT9vr2V-6RKxYajXFQELOjtWftxvO5oZBUgpY5ohHAyp4kHgsANF7iG5hFY7E0L89fWoDr-KMnOJ_W0vsDfXDPWMvJ0FnP2SerYhyWuNvZaqXRsPLxatWEDYNJHnBCKcbC_HZjIwsc_ENqvYEnPF_c6uqeMxFH17zfrVZCJZ1iWxK0D4O_wwxuJxC4LbD1oVeJymd2R5IyH4A9ENlABbzJDRMWtYgxU69031HRVr6rczBZcnNFCw2qDw1tKBSJV9Wp5RPZHqy-ThO4x-Aq6xT8YIa5d9EDamAfYqk0nz0oc547FqAhlUF0qJBQITj0cE=s893-no?authuser=0"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the bulk of
              the card's content.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
        <div class="card" style="background-color: rgb(192, 224, 255)">
          <img
            src="https://lh3.googleusercontent.com/ZdaBrzMx6-mpsnUKy6BvcBfSKuRF-JOkHG538PSdWY0aOjP2rOcL_nm_zqu0OIQYs03hRiUi820EofFEEUcmY_4DhUoqWiCP2tQjw7vyshWQg7WvsINw70nPrNgvKcTgcLYAY-Cv-x1BTg6xCgwycZ-DBPDi9zrkvu735o5pHgxyQA4-6PmOEsTCd-F9wjE_gi66O-mKiOZW6ediZpqno2h7hgJvDEpFnLdtx_rSduZbfj_9SUQ48WtzonLFMxBwSOm1Ge1wbx2c8o3BPVIDyOfhM9hE8LC31G1w7N2-XVKRcKSuO0ixrLEEwjJfb3z56ri6jaWN4wt--0YCw5EMEhvh1LyZl_ud8Oa6j7Bx8gRdReahR2rLEo_RusW41f_-UbheJCl8YT3cXcZIR6OcSvw7we4vTf05zx6X65Ta-EbVrB9q7zf7v2Pf6OpJHPOFp9DHjWOlqNhCdLVMFDYYBR8xz6AiyPMbEG0xhEsIGMoxgZSU5ACAkBP9TG01JSYMfOArultvMnjaTT9psg7sQeelMvwl6hSHUHDo7sPMjnMPBy2fa5bZkks8s0uQiwwkXclJxteaXciz9UQcwDzGwTICZlkdBUzpV6rdHAS9gI_txWkeHbMr9RFnfJnh2zWG-YTF__H7nildhZQtQxulGT9vr2V-6RKxYajXFQELOjtWftxvO5oZBUgpY5ohHAyp4kHgsANF7iG5hFY7E0L89fWoDr-KMnOJ_W0vsDfXDPWMvJ0FnP2SerYhyWuNvZaqXRsPLxatWEDYNJHnBCKcbC_HZjIwsc_ENqvYEnPF_c6uqeMxFH17zfrVZCJZ1iWxK0D4O_wwxuJxC4LbD1oVeJymd2R5IyH4A9ENlABbzJDRMWtYgxU69031HRVr6rczBZcnNFCw2qDw1tKBSJV9Wp5RPZHqy-ThO4x-Aq6xT8YIa5d9EDamAfYqk0nz0oc547FqAhlUF0qJBQITj0cE=s893-no?authuser=0"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the bulk of
              the card's content.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
        <div class="card" style="background-color: rgb(255, 192, 255)">
          <img
            src="https://lh3.googleusercontent.com/ZdaBrzMx6-mpsnUKy6BvcBfSKuRF-JOkHG538PSdWY0aOjP2rOcL_nm_zqu0OIQYs03hRiUi820EofFEEUcmY_4DhUoqWiCP2tQjw7vyshWQg7WvsINw70nPrNgvKcTgcLYAY-Cv-x1BTg6xCgwycZ-DBPDi9zrkvu735o5pHgxyQA4-6PmOEsTCd-F9wjE_gi66O-mKiOZW6ediZpqno2h7hgJvDEpFnLdtx_rSduZbfj_9SUQ48WtzonLFMxBwSOm1Ge1wbx2c8o3BPVIDyOfhM9hE8LC31G1w7N2-XVKRcKSuO0ixrLEEwjJfb3z56ri6jaWN4wt--0YCw5EMEhvh1LyZl_ud8Oa6j7Bx8gRdReahR2rLEo_RusW41f_-UbheJCl8YT3cXcZIR6OcSvw7we4vTf05zx6X65Ta-EbVrB9q7zf7v2Pf6OpJHPOFp9DHjWOlqNhCdLVMFDYYBR8xz6AiyPMbEG0xhEsIGMoxgZSU5ACAkBP9TG01JSYMfOArultvMnjaTT9psg7sQeelMvwl6hSHUHDo7sPMjnMPBy2fa5bZkks8s0uQiwwkXclJxteaXciz9UQcwDzGwTICZlkdBUzpV6rdHAS9gI_txWkeHbMr9RFnfJnh2zWG-YTF__H7nildhZQtQxulGT9vr2V-6RKxYajXFQELOjtWftxvO5oZBUgpY5ohHAyp4kHgsANF7iG5hFY7E0L89fWoDr-KMnOJ_W0vsDfXDPWMvJ0FnP2SerYhyWuNvZaqXRsPLxatWEDYNJHnBCKcbC_HZjIwsc_ENqvYEnPF_c6uqeMxFH17zfrVZCJZ1iWxK0D4O_wwxuJxC4LbD1oVeJymd2R5IyH4A9ENlABbzJDRMWtYgxU69031HRVr6rczBZcnNFCw2qDw1tKBSJV9Wp5RPZHqy-ThO4x-Aq6xT8YIa5d9EDamAfYqk0nz0oc547FqAhlUF0qJBQITj0cE=s893-no?authuser=0"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the bulk of
              the card's content.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
h1 {
  color: coral;
  text-align: center;
}
h4 {
  color: limegreen;
  text-align: center;
}
.container {
  display: grid;
  justify-content: center;
  grid-template-columns: auto auto auto;
  row-gap: 20px;
  column-gap: 50px;
}
.card {
  width: 18rem;
  scroll-behavior: smooth;
}
</style>
