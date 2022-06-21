<template>
    <div class="px-10 grid auto-rows-auto md:grid-cols-2 grid-flow-row md:gap-10 md:py-5 py-2">
        <!--Card 1-->
        <div class="rounded overflow-hidden shadow-lg hover:shadow-2xl pb-5">
                <div class="min-h-[40%]"><img class ="mx-auto md:scale-100 scale-75" src="../assets/img-card-1.jpg" alt="Mountain"></div>
                <div class="min-h-[60%] flex flex-col items-center space-y-6 md:pt-10 pt-5">
                <div class="font-bold md:text-xl mb-2 text-blue-900 text-xm">Storage as a Service</div>
                <div class="text-gray-700 text-base px-4 text-center hidden md:block">
                    Our service helps you consume next-generation storage on a gigabyte basis. You can allocate data in different performance and availability tiers depending on usage or value.
                </div>
                <div>
                    <button class="md:px-3 md:py-2 px-2 py-1 rounded-full text-blue-900 border border-blue-900 py-2 px-4 hover:text-pink-500 hover:border-pink-500 md:text-xl text-xs">Learn More</button>
                </div>
                </div>
        </div>
        <!--Card 2-->
        <div class="rounded overflow-hidden shadow-lg hover:shadow-2xl pb-5">
                <div class="min-h-[40%]"><img class ="mx-auto md:scale-100 scale-75" src="../assets/img-card-2.jpg" alt="Mountain"></div>
                <div class="min-h-[60%] flex flex-col items-center space-y-6 py-5">
                <div class="font-bold md:text-xl mb-2 text-blue-900 text-xm">AI Powered Search</div>
                <div class="text-gray-700 text-base px-4 text-center hidden md:block">
                    Our data search uses the latest machine learning techniques to create search engines that continuously learn from users and content, to drive intelligent search and auto visualize the result.
                </div>
                <div>
                    <button class="md:px-3 md:py-2 px-2 py-1 rounded-full text-blue-900 border border-blue-900 py-2 px-4 hover:text-pink-500 hover:border-pink-500 md:text-xl text-xs">Learn More</button>
                </div>
                </div>
        </div>

        <!--Card 3-->
        <div class="rounded overflow-hidden shadow-lg hover:shadow-2xl pb-5">
                <div class="min-h-[40%] mx-auto"><img class ="mx-auto md:scale-100 scale-75" src="../assets/img-card-3.jpg" alt="Mountain"></div>
                <div class="min-h-[60%] flex flex-col items-center space-y-6">
                <div class="font-bold md:text-xl mb-2 text-blue-900 text-xm">Data Visualization With AI</div>
                <div class="text-gray-700 text-base px-4 text-center hidden md:block">
                    Our AI analytics engine explore structure & relationships in data and visualize information to  help you accelerate detection of important and urgent business events, react in real-time
                </div>
                <div>
                    <button class="md:px-3 md:py-2 px-2 py-1 rounded-full text-blue-900 border border-blue-900 py-2 px-4 hover:text-pink-500 hover:border-pink-500 md:text-xl text-xs">Learn More</button>
                </div>
                </div>
        </div>

        <!--Card 4-->
        <div class="rounded overflow-hidden shadow-lg hover:shadow-2xl pb-5">
                <div class="min-h-[40%] mx-auto"><img class ="mx-auto md:scale-100 scale-75" src="../assets/img-card-4.jpg" alt="Mountain"></div>
                <div class="min-h-[60%] flex flex-col items-center space-y-6">
                <div class="font-bold md:text-xl mb-2 text-blue-900 text-xm">Workflow Scheduler</div>
                <div class="text-gray-700 text-base px-4 text-center hidden md:block">
                    With scheduler you set up scheduled units of work to be executed at defined times or regular intervals such as sending out a report email on a daily basis, weekly report generation
                </div>
                <div>
                    <button class="md:px-3 md:py-2 px-2 py-1 rounded-full text-blue-900 border border-blue-900 py-2 px-4 hover:text-pink-500 hover:border-pink-500 md:text-xl text-xs">Learn More</button>
                </div>
                </div>
        </div>

        <!--Card 5-->
        <div class="rounded overflow-hidden shadow-lg hover:shadow-2xl pb-5">
                <div class="min-h-[40%] mx-auto"><img class ="mx-auto md:scale-100 scale-75" src="../assets/img-card-5.jpg" alt="Mountain"></div>
                <div class="min-h-[60%] flex flex-col items-center space-y-6">
                <div class="font-bold md:text-xl mb-2 text-blue-900 text-xm">Security & Governance</div>
                <div class="text-gray-700 text-base px-4 text-center hidden md:block">
                    Protect the integrity and reliability of your data through governance policies. Keep your data compliant and audit-ready by building a clean, governed data lake.
                </div>
                <div>
                    <button class="md:px-3 md:py-2 px-2 py-1 rounded-full text-blue-900 border border-blue-900 py-2 px-4 hover:text-pink-500 hover:border-pink-500 md:text-xl text-xs">Learn More</button>
                </div>
                </div>
        </div>

        <!--Card 6-->
        <div class="rounded overflow-hidden shadow-lg hover:shadow-2xl pb-5">
                <div class="min-h-[40%] mx-auto"><img class ="mx-auto md:scale-100 scale-75" src="../assets/img-card-6.jpg" alt="Mountain"></div>
                <div class="min-h-[60%] flex flex-col items-center space-y-6">
                <div class="font-bold md:text-xl mb-2 text-blue-900 text-xm">Quick Setup</div>
                <div class="text-gray-700 text-base px-4 text-center hidden md:block">
                    With Pacific DataLake, you can move, store, catalog, and clean your data faster. You simply point Lake Formation at your data sources, and our AI Engine will take care of your data.
                </div>
                <div>
                    <button class="md:px-3 md:py-2 px-2 py-1 rounded-full text-blue-900 border border-blue-900 py-2 px-4 hover:text-pink-500 hover:border-pink-500 md:text-xl text-xs">Learn More</button>
                </div>
                </div>
        </div>
  </div>
</template>

<script lang="ts">
export default {
  name: 'Cards',
  data() {
    return {
    }
  },
  methods: {
  }
}
</script>