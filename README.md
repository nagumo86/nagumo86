<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>James Wilson - Software Engineer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
      tailwind.config = {
        theme: {
          extend: {
            colors: {
              primary: "#0891b2",
              secondary: "#6366f1",
            },
            borderRadius: {
              none: "0px",
              sm: "4px",
              DEFAULT: "8px",
              md: "12px",
              lg: "16px",
              xl: "20px",
              "2xl": "24px",
              "3xl": "32px",
              full: "9999px",
              button: "8px",
            },
          },
        },
      };
    </script>
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css"
    />
    <style>
      :where([class^="ri-"])::before { content: "\f3c2"; }
    </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/echarts/5.5.0/echarts.min.js"></script>
  </head>
  <body class="bg-gray-50 min-h-screen">
    <div class="max-w-5xl mx-auto px-4 py-12">
      <header class="text-center mb-16">
        <div class="relative w-32 h-32 mx-auto mb-6">
          <img
            src="https://public.readdy.ai/ai/img_res/718859d308d98dd708db25a08f0acc72.jpg"
            alt="Profile Picture"
            class="rounded-full w-full h-full object-cover shadow-lg"
          />
          <div
            class="absolute -bottom-2 -right-2 bg-green-500 w-6 h-6 rounded-full border-4 border-white"
          ></div>
        </div>
        <h1 class="text-4xl font-bold text-gray-900 mb-3">James Wilson</h1>
        <p class="text-lg text-gray-600 mb-6">
          Senior Software Engineer & Open Source Enthusiast
        </p>
        <div class="flex justify-center gap-4 mb-8">
          <a
            href="#"
            class="w-10 h-10 flex items-center justify-center bg-gray-100 rounded-full hover:bg-gray-200 transition-colors"
          >
            <i class="ri-github-line text-xl"></i>
          </a>
          <a
            href="#"
            class="w-10 h-10 flex items-center justify-center bg-gray-100 rounded-full hover:bg-gray-200 transition-colors"
          >
            <i class="ri-linkedin-line text-xl"></i>
          </a>
          <a
            href="#"
            class="w-10 h-10 flex items-center justify-center bg-gray-100 rounded-full hover:bg-gray-200 transition-colors"
          >
            <i class="ri-twitter-x-line text-xl"></i>
          </a>
          <a
            href="#"
            class="w-10 h-10 flex items-center justify-center bg-gray-100 rounded-full hover:bg-gray-200 transition-colors"
          >
            <i class="ri-mail-line text-xl"></i>
          </a>
        </div>
        <div class="flex justify-center gap-4">
          <div class="px-4 py-2 bg-white rounded-lg shadow-sm">
            <div class="text-sm text-gray-500">Profile Views</div>
            <div class="text-2xl font-bold text-gray-900">12.5k</div>
          </div>
          <div class="px-4 py-2 bg-white rounded-lg shadow-sm">
            <div class="text-sm text-gray-500">Repositories</div>
            <div class="text-2xl font-bold text-gray-900">86</div>
          </div>
          <div class="px-4 py-2 bg-white rounded-lg shadow-sm">
            <div class="text-sm text-gray-500">Contributions</div>
            <div class="text-2xl font-bold text-gray-900">1,247</div>
          </div>
        </div>
      </header>
      <section class="bg-white rounded-lg shadow-sm p-8 mb-8">
        <h2 class="text-2xl font-bold text-gray-900 mb-6">About Me</h2>
        <p class="text-gray-600 mb-6">
          Passionate software engineer with 8+ years of experience in full-stack
          development. Currently leading the frontend team at TechCorp, focusing
          on building scalable and performant web applications. Open source
          contributor and advocate for clean code practices.
        </p>
        <div class="grid grid-cols-2 gap-6">
          <div>
            <h3 class="font-semibold text-gray-900 mb-3">Current Focus</h3>
            <ul class="space-y-2 text-gray-600">
              <li class="flex items-center gap-2">
                <i class="ri-check-line text-green-500"></i>
                Cloud Native Applications
              </li>
              <li class="flex items-center gap-2">
                <i class="ri-check-line text-green-500"></i>
                Microservices Architecture
              </li>
              <li class="flex items-center gap-2">
                <i class="ri-check-line text-green-500"></i>
                Performance Optimization
              </li>
            </ul>
          </div>
          <div>
            <h3 class="font-semibold text-gray-900 mb-3">Learning</h3>
            <ul class="space-y-2 text-gray-600">
              <li class="flex items-center gap-2">
                <i class="ri-arrow-right-line text-primary"></i>
                Rust Programming
              </li>
              <li class="flex items-center gap-2">
                <i class="ri-arrow-right-line text-primary"></i>
                WebAssembly
              </li>
              <li class="flex items-center gap-2">
                <i class="ri-arrow-right-line text-primary"></i>
                System Design
              </li>
            </ul>
          </div>
        </div>
      </section>

      <section class="bg-white rounded-lg shadow-sm p-8 mb-8">
        <h2 class="text-2xl font-bold text-gray-900 mb-6">Technical Skills</h2>
        <div class="grid grid-cols-2 gap-8">
          <div>
            <h3 class="font-semibold text-gray-900 mb-4">Languages</h3>
            <div class="space-y-4">
              <div>
                <div class="flex justify-between mb-1">
                  <span class="text-gray-600">JavaScript/TypeScript</span>
                  <span class="text-gray-500">95%</span>
                </div>
                <div class="h-2 bg-gray-200 rounded-full">
                  <div
                    class="h-2 bg-primary rounded-full"
                    style="width: 95%"
                  ></div>
                </div>
              </div>
              <div>
                <div class="flex justify-between mb-1">
                  <span class="text-gray-600">Python</span>
                  <span class="text-gray-500">85%</span>
                </div>
                <div class="h-2 bg-gray-200 rounded-full">
                  <div
                    class="h-2 bg-primary rounded-full"
                    style="width: 85%"
                  ></div>
                </div>
              </div>
              <div>
                <div class="flex justify-between mb-1">
                  <span class="text-gray-600">Go</span>
                  <span class="text-gray-500">75%</span>
                </div>
                <div class="h-2 bg-gray-200 rounded-full">
                  <div
                    class="h-2 bg-primary rounded-full"
                    style="width: 75%"
                  ></div>
                </div>
              </div>
            </div>
          </div>
          <div>
            <h3 class="font-semibold text-gray-900 mb-4">Frameworks & Tools</h3>
            <div class="flex flex-wrap gap-2">
              <span class="px-3 py-1 bg-gray-100 rounded-full text-gray-600"
                >React</span
              >
              <span class="px-3 py-1 bg-gray-100 rounded-full text-gray-600"
                >Vue.js</span
              >
              <span class="px-3 py-1 bg-gray-100 rounded-full text-gray-600"
                >Node.js</span
              >
              <span class="px-3 py-1 bg-gray-100 rounded-full text-gray-600"
                >Docker</span
              >
              <span class="px-3 py-1 bg-gray-100 rounded-full text-gray-600"
                >Kubernetes</span
              >
              <span class="px-3 py-1 bg-gray-100 rounded-full text-gray-600"
                >AWS</span
              >
              <span class="px-3 py-1 bg-gray-100 rounded-full text-gray-600"
                >GraphQL</span
              >
              <span class="px-3 py-1 bg-gray-100 rounded-full text-gray-600"
                >MongoDB</span
              >
            </div>
          </div>
        </div>
      </section>

      <section class="bg-white rounded-lg shadow-sm p-8 mb-8">
        <h2 class="text-2xl font-bold text-gray-900 mb-6">Featured Projects</h2>
        <div class="grid grid-cols-2 gap-6">
          <div class="border border-gray-200 rounded-lg overflow-hidden">
            <img
              src="https://public.readdy.ai/ai/img_res/1c3860606e2f458b60c94ed210d05d0a.jpg"
              alt="Project Preview"
              class="w-full h-48 object-cover"
            />
            <div class="p-4">
              <h3 class="font-semibold text-gray-900 mb-2">CloudDash</h3>
              <p class="text-gray-600 text-sm mb-4">
                A modern cloud infrastructure monitoring dashboard with
                real-time metrics and alerts.
              </p>
              <div class="flex flex-wrap gap-2 mb-4">
                <span
                  class="px-2 py-1 bg-gray-100 rounded text-xs text-gray-600"
                  >React</span
                >
                <span
                  class="px-2 py-1 bg-gray-100 rounded text-xs text-gray-600"
                  >Go</span
                >
                <span
                  class="px-2 py-1 bg-gray-100 rounded text-xs text-gray-600"
                  >AWS</span
                >
              </div>
              <div class="flex gap-3">
                <a href="#" class="text-primary hover:text-primary-dark">
                  <i class="ri-github-line"></i> Source
                </a>
                <a href="#" class="text-primary hover:text-primary-dark">
                  <i class="ri-external-link-line"></i> Demo
                </a>
              </div>
            </div>
          </div>
          <div class="border border-gray-200 rounded-lg overflow-hidden">
            <img
              src="https://public.readdy.ai/ai/img_res/8db9f7907d2622ae23d3ebdc5a1c2e20.jpg"
              alt="Project Preview"
              class="w-full h-48 object-cover"
            />
            <div class="p-4">
              <h3 class="font-semibold text-gray-900 mb-2">ShopSmart</h3>
              <p class="text-gray-600 text-sm mb-4">
                An e-commerce platform with AI-powered product recommendations
                and real-time inventory management.
              </p>
              <div class="flex flex-wrap gap-2 mb-4">
                <span
                  class="px-2 py-1 bg-gray-100 rounded text-xs text-gray-600"
                  >Vue.js</span
                >
                <span
                  class="px-2 py-1 bg-gray-100 rounded text-xs text-gray-600"
                  >Node.js</span
                >
                <span
                  class="px-2 py-1 bg-gray-100 rounded text-xs text-gray-600"
                  >MongoDB</span
                >
              </div>
              <div class="flex gap-3">
                <a href="#" class="text-primary hover:text-primary-dark">
                  <i class="ri-github-line"></i> Source
                </a>
                <a href="#" class="text-primary hover:text-primary-dark">
                  <i class="ri-external-link-line"></i> Demo
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="bg-white rounded-lg shadow-sm p-8 mb-8">
        <h2 class="text-2xl font-bold text-gray-900 mb-6">GitHub Activity</h2>
        <div class="grid grid-cols-2 gap-6">
          <div>
            <div id="contributionChart" class="w-full h-64"></div>
          </div>
          <div>
            <div id="languageChart" class="w-full h-64"></div>
          </div>
        </div>
      </section>
      <footer class="text-center">
        <p class="text-gray-600 mb-4">
          "Code is like humor. When you have to explain it, it's bad." - Cory
          House
        </p>
        <p class="text-gray-500 text-sm">Last updated: March 16, 2025</p>
      </footer>
    </div>

    <script>
      const contributionChart = echarts.init(
        document.getElementById("contributionChart"),
      );
      const languageChart = echarts.init(document.getElementById("languageChart"));

      const contributionOption = {
        animation: false,
        title: {
          text: "Contributions",
          left: "center",
          textStyle: {
            color: "#1f2937",
          },
        },
        tooltip: {
          trigger: "axis",
          backgroundColor: "rgba(255, 255, 255, 0.9)",
          textStyle: {
            color: "#1f2937",
          },
        },
        xAxis: {
          type: "category",
          data: ["Jan", "Feb", "Mar", "Apr", "May", "Jun"],
        },
        yAxis: {
          type: "value",
        },
        series: [
          {
            data: [150, 230, 224, 218, 135, 147],
            type: "line",
            smooth: true,
            symbolSize: 0,
            areaStyle: {
              color: new echarts.graphic.LinearGradient(0, 0, 0, 1, [
                {
                  offset: 0,
                  color: "rgba(87, 181, 231, 0.3)",
                },
                {
                  offset: 1,
                  color: "rgba(87, 181, 231, 0.1)",
                },
              ]),
            },
            lineStyle: {
              color: "rgba(87, 181, 231, 1)",
            },
          },
        ],
      };

      const languageOption = {
        animation: false,
        title: {
          text: "Languages",
          left: "center",
          textStyle: {
            color: "#1f2937",
          },
        },
        tooltip: {
          trigger: "item",
          backgroundColor: "rgba(255, 255, 255, 0.9)",
          textStyle: {
            color: "#1f2937",
          },
        },
        series: [
          {
            type: "pie",
            radius: "70%",
            data: [
              { value: 40, name: "JavaScript" },
              { value: 30, name: "Python" },
              { value: 20, name: "Go" },
              { value: 10, name: "Others" },
            ],
            itemStyle: {
              borderRadius: 8,
            },
            color: [
              "rgba(87, 181, 231, 1)",
              "rgba(141, 211, 199, 1)",
              "rgba(251, 191, 114, 1)",
              "rgba(252, 141, 98, 1)",
            ],
          },
        ],
      };
      contributionChart.setOption(contributionOption);
      languageChart.setOption(languageOption);

      window.addEventListener("resize", () => {
        contributionChart.resize();
        languageChart.resize();
      });
    </script>
  </body>
</html>
