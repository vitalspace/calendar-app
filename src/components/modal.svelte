<div class="flex h-screen items-center justify-center bg-[conic-gradient(at_bottom_left,_var(--tw-gradient-stops))] from-slate-300 via-lime-50 to-rose-700">
    <div class="w-full space-y-8 rounded-xl bg-gradient-to-tr from-red-200 via-white to-white px-4 py-4 font-bold text-gray-600 sm:w-3/5 md:w-2/5 xl:w-1/4">
      <div>
        <h2 class="text-2xl">Create New Reminder</h2>
      </div>
      <div class="flex flex-wrap border-b-2 pb-4">
        <label class="text-[#1d3242]" for="">Text Name</label>
        <input class="w-full bg-inherit" type="text" placeholder="Desing app" />
      </div>
  
      <div class="flex flex-wrap border-b-2 pb-4">
        <label class="text-red-400" for="description">Description</label>
        <textarea class="w-full bg-inherit" name="description" id="" rows="5" placeholder="">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nesciunt magnam sit labore quam. Enim facilis provident sed facere sequi et fugiat culpa eaque natus fugit quidem, ex eos excepturi.</textarea>
      </div>
      <div class="flex justify-between rounded-lg bg-[#fdfbfd] px-4 py-4">
        <p>Remind me</p>
        <button>
          <label class="relative inline-flex cursor-pointer">
            <input type="checkbox" value="" class="peer sr-only" checked />
            <div class="dark:peer-focus:ring-[ #fa696f] peer h-6 w-11 rounded-full bg-gray-200 after:absolute after:left-[2px] after:top-0.5 after:h-5 after:w-5 after:rounded-full after:border after:border-gray-300 after:bg-white after:transition-all after:content-[''] peer-checked:bg-[#fa696f] peer-checked:after:translate-x-full peer-checked:after:border-white peer-focus:ring-4 peer-focus:ring-blue-300 dark:border-gray-600 dark:bg-gray-700"></div>
          </label>
        </button>
      </div>
  
      <div class="flex justify-between text-white">
        <div class="flex items-center justify-center space-x-4 rounded-lg bg-[#32bfe9] px-6 py-2">
          <div>icon</div>
          <div>
            <p>12:30pm</p>
            <p>Task Start</p>
          </div>
        </div>
        <div class="flex items-center justify-center space-x-4 rounded-lg bg-[#688af0] px-6 py-2">
          <div>icon</div>
          <div>
            <p>12:30pm</p>
            <p>Task Start</p>
          </div>
        </div>
      </div>
  
      <div class="flex items-center justify-between">
        <div>
          <p>Text Color</p>
        </div>
        <div class="flex space-x-1">
          <div class="rounded-lg bg-[#688af0] px-6 py-6"></div>
          <div class="rounded-lg bg-[#fe7e74] px-6 py-6"></div>
          <div class="rounded-lg bg-[#28c8f6] px-6 py-6"></div>
          <div class="rounded-lg bg-[#feb175] px-6 py-6"></div>
        </div>
      </div>
  
      <button class="w-full rounded-lg bg-[#fc676e] py-4 text-center text-white shadow-lg shadow-[#fc676e]">Create Task</button>
    </div>
  </div>
  