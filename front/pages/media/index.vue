<template>
  <UiHeader></UiHeader>

  <section class="flex h-full mt-32 justify-evenly">
    <div
      class="gap-[94px] items-start flex-col [@media(min-width:1188px)]:flex-row w-full flex"
    >
      <div class="ga.5 flex-col items-start flex-1 min-w-0 flex">
        <UiTag></UiTag>
        <div class="gap-2.5 flex-row justify-center items-start p-2.5 flex">
          <div class="gap-2.5 flex-col items-start p-2.5 flex">
            <div class="w-[280px] h-[441px] relative rounded-xl border">
              <img src="" alt="" />
            </div>
            <span
              class="categoriesDuration font-semibold text-[#eaeff5] text-left w-full h-[21px]"
            >
              Categories - Duration</span
            >
          </div>
          <div class="gap-8 flex-col items-start p-2.5 flex">
            <div
              class="gap-2.5 flex-row justify-between items-center w-full flex"
            >
              <h2 class="text-5xl font-bold text-[#eaeff5] text-left">
                Rogue One
              </h2>

              <!-- Rating stars -->
              <div
                class="gap-1.5 flex-row w-40 justify-end items-start flex"
              ></div>
              <!-- Rating stars -->
            </div>
            <div class="gap-4 flex-row items-center w-full flex">
              <UiBtnPrimary :btnText="'Watchlist'" size="medium"></UiBtnPrimary>
              <UiBtnSecondary
                :btnText="'Déjà vu'"
                size="medium"
              ></UiBtnSecondary>
            </div>
            <div class="2608853 gap-2.5 flex-col items-start w-full py-6 flex">
              <div class="2608844 gap-[9px] flex-col items-start flex">
                <span
                  class="description text-lg font-semibold text-[#eaeff5] text-left w-full h-[21px]"
                  >Description
                </span>
                <span
                  class="loremIpsumDolorSitAmetConsecteturAdipiscingElitSedDoEiusmodTemporIncididuntUtLaboreEtDoloreMagnaAliquaUtEnimAdMinimVeniamQuisNostrudExercitation text-[#78889b] text-left w-[432px]"
                  >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam, quis nostrud exercitation .
                </span>
              </div>
              <div class="gap-2.5 flex-col items-start w-full flex">
                <span
                  class="text-lg font-semibold text-[#eaeff5] text-left w-full h-[21px]"
                  >Réalisateur</span
                >
                <span class="text-[#78889b] text-left w-full"
                  >Steven Spielberg</span
                >
              </div>
            </div>
            <div class="gap-2.5 flex-col items-start flex">
              <!-- <img
                src="/images/paramountLogo1.png"
                onerror="this.src='http://svgur.com/i/x4x.svg'"
                class="paramountLogo1 w-[77.11px] h-12 relative object-cover "
              /> -->
            </div>
          </div>
        </div>
      </div>
      <div class="gap-2 flex-col items-center p-2.5 flex">
        <div class="gap-2.5 flex-col items-start flex">
          <div class="gap-2.5 flex-col items-start flex">
            <span
              class="text-lg font-semibold text-[#eaeff5] text-left w-full h-[21px]"
              >Acteurs</span
            >
          </div>
          <div class="gap-6 flex-row items-start py-2.5 flex">
            <div class="gap-4 flex-col justify-center items-center flex">
              <svg
                width="69"
                height="68"
                viewBox="0 0 69 68"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="34.7305" cy="34" r="34" fill="#D9D9D9" />
              </svg>
              <span class="text-sm text-[#78889b] text-center w-full"
                >Matt Damon</span
              >
            </div>
            <div class="gap-4 flex-col justify-center items-center flex">
              <svg
                width="69"
                height="68"
                viewBox="0 0 69 68"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="34.7305" cy="34" r="34" fill="#D9D9D9" />
              </svg>
              <span class="mattDamon text-sm text-[#78889b] text-center w-full"
                >Matt Damon</span
              >
            </div>
            <div class="gap-4 flex-col justify-center items-center flex">
              <svg
                width="69"
                height="68"
                viewBox="0 0 69 68"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="34.7305" cy="34" r="34" fill="#D9D9D9" />
              </svg>
              <span class="text-sm text-[#78889b] text-center w-full"
                >Matt Damon</span
              >
            </div>
          </div>
          <div class="gap-6 flex-row items-start py-2.5 flex">
            <div class="gap-4 flex-col justify-center items-center flex">
              <svg
                width="69"
                height="68"
                viewBox="0 0 69 68"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="34.7305" cy="34" r="34" fill="#D9D9D9" />
              </svg>
              <span class="text-sm text-[#78889b] text-center w-full"
                >Matt Damon</span
              >
            </div>
            <div class="gap-4 flex-col justify-center items-center flex">
              <svg
                width="69"
                height="68"
                viewBox="0 0 69 68"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="34.7305" cy="34" r="34" fill="#D9D9D9" />
              </svg>
              <span class="text-sm text-[#78889b] text-center w-full"
                >Matt Damon</span
              >
            </div>
            <div class="gap-4 flex-col justify-center items-center flex">
              <svg
                width="69"
                height="68"
                viewBox="0 0 69 68"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="34.7305" cy="34" r="34" fill="#D9D9D9" />
              </svg>
              <span class="text-sm text-[#78889b] text-center w-full"
                >Matt Damon</span
              >
            </div>
          </div>
          <div class="gap-6 flex-row items-start py-2.5 flex">
            <div class="gap-4 flex-col justify-center items-center flex">
              <svg
                width="69"
                height="68"
                viewBox="0 0 69 68"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="34.7305" cy="34" r="34" fill="#D9D9D9" />
              </svg>
              <span class="mattDamon text-sm text-[#78889b] text-center w-full"
                >Matt Damon</span
              >
            </div>
            <div class="gap-4 flex-col justify-center items-center flex">
              <svg
                width="69"
                height="68"
                viewBox="0 0 69 68"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="34.7305" cy="34" r="34" fill="#D9D9D9" />
              </svg>
              <span class="text-sm text-[#78889b] text-center w-full"
                >Matt Damon</span
              >
            </div>
            <div class="gap-4 flex-col justify-center items-center flex">
              <svg
                width="69"
                height="68"
                viewBox="0 0 69 68"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="34.7305" cy="34" r="34" fill="#D9D9D9" />
              </svg>
              <span class="text-sm text-[#78889b] text-center w-full"
                >Matt Damon</span
              >
            </div>
          </div>
        </div>
        <div class="gap-2.5 flex-col items-start py-2.5 flex">
          <div class="gap-2.5 flex-col items-start w-full flex">
            <span
              class="text-lg font-semibold text-[#eaeff5] text-left w-full h-[21px]"
              >Bande annonce</span
            >
            <iframe
              class="rounded-lg border"
              src="https://www.youtube.com/watch?app=desktop&v=Ni3k8xoFV-o"
            ></iframe>
          </div>
          <svg
            class="738x416webp"
            width="264"
            height="149"
            viewBox="0 0 264 149"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          ></svg>
        </div>
      </div>
    </div>
  </section>
</template>
