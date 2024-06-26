<template>

<div class="w-96 h-96 flex-col justify-start items-start gap-8 inline-flex">
  <div class="self-stretch h-20 flex-col justify-start items-center gap-6 flex">
    <div class="self-stretch h-20 flex-col justify-start items-start gap-3 flex">
      <div class="self-stretch text-gray-900 text-4xl font-semibold font-['Inter'] leading-10">Log in</div>
      <div class="self-stretch text-slate-600 text-base font-normal font-['Inter'] leading-normal">Welcome back! Please enter your details.</div>
    </div>
  </div>
  <div class="self-stretch h-80 rounded-xl flex-col justify-start items-center gap-6 flex">
    <div class="self-stretch h-40 flex-col justify-start items-start gap-5 flex">
      <div class="self-stretch h-16 flex-col justify-start items-start gap-1.5 flex">
        <div class="self-stretch h-16 flex-col justify-start items-start gap-1.5 flex">
          <div class="text-slate-700 text-sm font-medium font-['Inter'] leading-tight">Email</div>
          <div class="self-stretch px-3.5 py-2.5 bg-white rounded-lg shadow border border-gray-300 justify-start items-center gap-2 inline-flex">
            <div class="grow shrink basis-0 h-6 justify-start items-center gap-2 flex">
              <div class="grow shrink basis-0 text-gray-500 text-base font-normal font-['Inter'] leading-normal">Enter your email</div>
            </div>
          </div>
        </div>
      </div>
      <div class="self-stretch h-16 flex-col justify-start items-start gap-1.5 flex">
        <div class="self-stretch h-16 flex-col justify-start items-start gap-1.5 flex">
          <div class="text-slate-700 text-sm font-medium font-['Inter'] leading-tight">Password</div>
          <div class="self-stretch px-3.5 py-2.5 bg-white rounded-lg shadow border border-gray-300 justify-start items-center gap-2 inline-flex">
            <div class="grow shrink basis-0 h-6 justify-start items-center gap-2 flex">
              <div class="grow shrink basis-0 text-gray-500 text-base font-normal font-['Inter'] leading-normal">••••••••</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="self-stretch justify-start items-center inline-flex">
      <div class="grow shrink basis-0 h-5 justify-start items-start gap-2 flex">
        <div class="pt-0.5 justify-center items-center flex">
          <div class="w-4 h-4 relative bg-white rounded border border-gray-300"></div>
        </div>
        <div class="grow shrink basis-0 flex-col justify-start items-start inline-flex">
          <div class="self-stretch text-slate-700 text-sm font-medium font-['Inter'] leading-tight">Remember for 30 days</div>
        </div>
      </div>
      <div class="w-28 self-stretch justify-center items-center gap-2 flex">
        <div class="text-sky-600 text-sm font-semibold font-['Inter'] leading-tight">Forgot password</div>
      </div>
    </div>
    <div class="self-stretch h-24 flex-col justify-start items-start gap-4 flex">
      <div class="self-stretch px-4 py-2.5 bg-sky-600 rounded-lg shadow border border-sky-600 justify-center items-center gap-2 inline-flex">
        <div class="text-white text-base font-semibold font-['Inter'] leading-normal">Sign in</div>
      </div>
      <div class="self-stretch h-11 flex-col justify-center items-center gap-3 flex">
        <div class="self-stretch px-4 py-2.5 bg-white rounded-lg shadow border border-sky-600 justify-center items-center gap-3 inline-flex">
          <div class="text-sky-600 text-base font-semibold font-['Inter'] leading-normal">Sign in with Health Worker ID</div>
        </div>
      </div>
    </div>
  </div>
  <div class="self-stretch justify-center items-baseline gap-1 inline-flex">
    <div class="text-slate-600 text-sm font-normal font-['Inter'] leading-tight">Don’t have an account?</div>
    <div class="justify-center items-center gap-2 flex">
      <div class="text-sky-600 text-sm font-semibold font-['Inter'] leading-tight">Sign up</div>
    </div>
  </div>
</div>
</template>