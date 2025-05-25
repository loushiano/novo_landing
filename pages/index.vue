<template>
  <!-- Header -->
  <header
    id="header"
    class="fixed w-full bg-white shadow-sm z-50 transition-all duration-300"
  >
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between items-center py-4">
        <div class="flex items-center">
          <span class="text-2xl font-bold text-primary cursor-pointer"
            >Novoprog</span
          >
        </div>

        <!-- Desktop Navigation -->
        <nav class="hidden md:flex space-x-8">
          <a
            href="#services"
            class="text-gray-600 hover:text-primary transition-colors cursor-pointer"
            >Services</a
          >
          <a
            href="#how-it-works"
            class="text-gray-600 hover:text-primary transition-colors cursor-pointer"
            >How It Works</a
          >
          <a
            href="#testimonials-section"
            class="text-gray-600 hover:text-primary transition-colors cursor-pointer"
            >Testimonials</a
          >

          <a
            href="#faq"
            class="text-gray-600 hover:text-primary transition-colors cursor-pointer"
            >FAQ</a
          >
        </nav>

        <div class="hidden md:block">
          <a
            href="#contact"
            class="px-5 py-2 bg-primary text-white rounded-md hover:bg-indigo-600 transition-colors cursor-pointer"
            >Contact Us</a
          >
        </div>

        <!-- Mobile Menu Button -->
        <button
          id="mobile-menu-button"
          class="md:hidden text-gray-500 focus:outline-none"
        >
          <i class="fa-solid fa-bars text-2xl"></i>
        </button>
      </div>
    </div>

    <!-- Mobile Navigation -->
    <div
      id="mobile-menu"
      class="md:hidden hidden bg-white border-t border-gray-200"
    >
      <div class="container mx-auto px-4 py-3 space-y-3">
        <a
          href="#services"
          class="block py-2 text-gray-600 hover:text-primary cursor-pointer"
          >Services</a
        >
        <a
          href="#how-it-works"
          class="block py-2 text-gray-600 hover:text-primary cursor-pointer"
          >How It Works</a
        >
        <a
          href="#case-studies"
          class="block py-2 text-gray-600 hover:text-primary cursor-pointer"
          >Case Studies</a
        >
        <a
          href="#pricing"
          class="block py-2 text-gray-600 hover:text-primary cursor-pointer"
          >Pricing</a
        >
        <a
          href="#faq"
          class="block py-2 text-gray-600 hover:text-primary cursor-pointer"
          >FAQ</a
        >
        <a
          href="#contact"
          class="block py-2 text-primary font-medium cursor-pointer"
          >Contact Us</a
        >
      </div>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="hero" class="pt-28 pb-20 md:pt-32 md:pb-24 bg-light">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex flex-col md:flex-row items-center">
        <div class="md:w-1/2 mb-10 md:mb-0">
          <h1
            class="text-4xl md:text-5xl lg:text-6xl font-bold leading-tight mb-6"
          >
            Take Your Business to the Next Level
          </h1>
          <p class="text-xl text-gray-600 mb-8 max-w-xl">
            We transform your business challenges into innovative software
            solutions that drive growth and efficiency
          </p>
          <a
            href="#contact"
            class="inline-block px-8 py-4 bg-primary text-white font-medium rounded-md shadow-lg hover:bg-indigo-600 hover:shadow-xl transition-all transform hover:-translate-y-1 cursor-pointer"
          >
            Get Your Free Consultation
          </a>
        </div>
        <div class="md:w-1/2">
          <div class="relative">
            <img
              class="w-full h-auto rounded-lg shadow-xl transform transition-transform hover:scale-[1.02]"
              src="https://storage.googleapis.com/uxpilot-auth.appspot.com/e436a10dc8-c48dcbc2eff75e20b35c.png"
              alt="modern abstract illustration showing collaboration between AI systems and humans, digital interface with human and AI agents working together, futuristic, professional, blue and purple tones"
            />
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="py-20 bg-white">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-16">
        <h2 class="text-3xl md:text-4xl font-bold mb-4">Our Services</h2>
        <p class="text-xl text-gray-600 max-w-3xl mx-auto">
          Custom software development that propels your business forward using
          cutting-edge technology and proven methodologies
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-3 gap-6 max-w-6xl mx-auto">
        <!-- Service Card 1 -->
        <div
          id="service-card-1"
          class="bg-white rounded-lg shadow-md hover:shadow-lg p-6 md:p-8 transition-all duration-300"
        >
          <div class="text-primary text-4xl mb-6">
            <i class="fa-solid fa-code"></i>
          </div>
          <h3 class="text-xl md:text-2xl font-bold mb-4">
            Custom Software Development
          </h3>
          <p class="text-gray-600">
            Tailored software solutions designed to address your unique business
            challenges and opportunities.
          </p>
        </div>

        <!-- Service Card 2 -->
        <div
          id="service-card-2"
          class="bg-white rounded-lg shadow-md hover:shadow-lg p-6 md:p-8 transition-all duration-300"
        >
          <div class="text-primary text-4xl mb-6">
            <i class="fa-solid fa-robot"></i>
          </div>
          <h3 class="text-xl md:text-2xl font-bold mb-4">
            AI Agents & Intelligent Systems
          </h3>
          <p class="text-gray-600">
            Build custom AI agents that automate complex tasks, make intelligent
            decisions, and integrate seamlessly with your existing workflows to
            boost productivity.
          </p>
        </div>

        <!-- Service Card 3 -->
        <div
          id="service-card-3"
          class="bg-white rounded-lg shadow-md hover:shadow-lg p-6 md:p-8 transition-all duration-300"
        >
          <div class="text-primary text-4xl mb-6">
            <i class="fa-solid fa-gears"></i>
          </div>
          <h3 class="text-xl md:text-2xl font-bold mb-4">
            Workflow Automation &amp; Integration
          </h3>
          <p class="text-gray-600">
            Streamline operations by connecting your systems and automating
            repetitive tasks for maximum efficiency.
          </p>
        </div>

        <!-- Service Card 4 -->
        <div
          id="service-card-4"
          class="bg-white rounded-lg shadow-md hover:shadow-lg p-6 md:p-8 transition-all duration-300"
        >
          <div class="text-primary text-4xl mb-6">
            <i class="fa-solid fa-plug"></i>
          </div>
          <h3 class="text-xl md:text-2xl font-bold mb-4">
            AI Integration Services
          </h3>
          <p class="text-gray-600">
            Seamlessly integrate AI capabilities into your existing systems,
            from ChatGPT APIs to custom machine learning models.
          </p>
        </div>

        <!-- Service Card 5 -->
        <div
          id="service-card-5"
          class="bg-white rounded-lg shadow-md hover:shadow-lg p-6 md:p-8 transition-all duration-300"
        >
          <div class="text-primary text-4xl mb-6">
            <i class="fa-solid fa-lightbulb"></i>
          </div>
          <h3 class="text-xl md:text-2xl font-bold mb-4">
            AI Strategy Consulting
          </h3>
          <p class="text-gray-600">
            Get expert guidance on how AI can transform your business processes,
            reduce costs, and create new revenue opportunities.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- How It Works Section -->
  <section id="how-it-works" class="py-20 bg-gray-50">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-16">
        <h2 class="text-3xl md:text-4xl font-bold mb-4">How It Works</h2>
        <p class="text-xl text-gray-600 max-w-3xl mx-auto">
          Our proven development process leverages hybrid AI-human coding to
          deliver faster, more reliable results
        </p>
      </div>

      <div class="relative">
        <!-- Timeline Line -->
        <div
          class="hidden md:block absolute left-1/2 top-0 bottom-0 w-1 bg-gray-200 transform -translate-x-1/2"
        ></div>

        <div class="space-y-12 md:space-y-0">
          <!-- Step 1 -->
          <div
            id="step-1"
            class="relative flex flex-col md:flex-row items-center"
          >
            <div class="md:w-1/2 md:pr-12 mb-8 md:mb-0 md:text-right">
              <div class="bg-white p-6 rounded-lg shadow-md inline-block">
                <div class="text-primary text-3xl mb-4">
                  <i class="fa-solid fa-lightbulb"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Discovery &amp; Strategy</h3>
                <p class="text-gray-600">
                  We analyze your business challenges and opportunities to
                  define the perfect software solution for your growth.
                </p>
              </div>
            </div>

            <div
              class="md:absolute md:left-1/2 md:transform md:-translate-x-1/2 z-10 bg-primary text-white w-12 h-12 rounded-full flex items-center justify-center text-xl font-bold shadow-lg"
            >
              1
            </div>

            <div class="md:w-1/2 md:pl-12 hidden md:block"></div>
          </div>

          <!-- Step 2 -->
          <div
            id="step-2"
            class="relative flex flex-col md:flex-row items-center md:mt-24"
          >
            <div class="md:w-1/2 md:pr-12 hidden md:block"></div>

            <div
              class="md:absolute md:left-1/2 md:transform md:-translate-x-1/2 z-10 bg-primary text-white w-12 h-12 rounded-full flex items-center justify-center text-xl font-bold shadow-lg"
            >
              2
            </div>

            <div class="md:w-1/2 md:pl-12 mb-8 md:mb-0">
              <div class="bg-white p-6 rounded-lg shadow-md inline-block">
                <div class="text-primary text-3xl mb-4">
                  <i class="fa-solid fa-wand-magic-sparkles"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">
                  Rapid Prototyping &amp; Design
                </h3>
                <p class="text-gray-600">
                  Using our hybrid development approach, we quickly create
                  prototypes and designs that bring your vision to life.
                </p>
              </div>
            </div>
          </div>

          <!-- Step 3 -->
          <div
            id="step-3"
            class="relative flex flex-col md:flex-row items-center md:mt-24"
          >
            <div class="md:w-1/2 md:pr-12 mb-8 md:mb-0 md:text-right">
              <div class="bg-white p-6 rounded-lg shadow-md inline-block">
                <div class="text-primary text-3xl mb-4">
                  <i class="fa-solid fa-code-branch"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">
                  Development &amp; Testing
                </h3>
                <p class="text-gray-600">
                  Our expert team builds robust, scalable solutions with
                  continuous testing to ensure quality and reliability.
                </p>
              </div>
            </div>

            <div
              class="md:absolute md:left-1/2 md:transform md:-translate-x-1/2 z-10 bg-primary text-white w-12 h-12 rounded-full flex items-center justify-center text-xl font-bold shadow-lg"
            >
              3
            </div>

            <div class="md:w-1/2 md:pl-12 hidden md:block"></div>
          </div>

          <!-- Step 4 -->
          <div
            id="step-4"
            class="relative flex flex-col md:flex-row items-center md:mt-24"
          >
            <div class="md:w-1/2 md:pr-12 hidden md:block"></div>

            <div
              class="md:absolute md:left-1/2 md:transform md:-translate-x-1/2 z-10 bg-primary text-white w-12 h-12 rounded-full flex items-center justify-center text-xl font-bold shadow-lg"
            >
              4
            </div>

            <div class="md:w-1/2 md:pl-12">
              <div class="bg-white p-6 rounded-lg shadow-md inline-block">
                <div class="text-primary text-3xl mb-4">
                  <i class="fa-solid fa-rocket"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Launch &amp; Support</h3>
                <p class="text-gray-600">
                  We deploy your solution and provide ongoing support to ensure
                  it continues driving your business success.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Case Studies Section -->
  <section id="testimonials-section" class="py-20 bg-white">
    <div class="container mx-auto px-4">
      <div class="text-center mb-16">
        <h2 class="text-3xl text-neutral-800 mb-4">What Our Clients Say</h2>
        <p class="text-lg text-neutral-600 max-w-3xl mx-auto">
          Don't just take our word for it—hear from the businesses we've helped
          succeed.
        </p>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-neutral-50 p-8 rounded-lg">
          <div class="flex items-center mb-6">
            <img
              src="https://d22m7af16es7fs.cloudfront.net/arnav.png"
              alt="Client"
              class="w-12 h-12 rounded-full mr-4"
            />
            <div>
              <h4>Arnav Khurana</h4>
              <p class="text-neutral-600 text-sm">CTO, Lime Group Inc.</p>
            </div>
          </div>
          <p class="text-neutral-700 mb-4">
            "NovoProg delivered our AI analytics platform in half the time
            and at 40% less cost than we budgeted. The quality exceeded our
            expectations."
          </p>
          <div class="flex">
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
          </div>
        </div>
        <div class="bg-neutral-50 p-8 rounded-lg">
          <div class="flex items-center mb-6">
            <img
              src="https://d22m7af16es7fs.cloudfront.net/mhadad.jpeg"
              alt="Client"
              class="w-12 h-12 rounded-full mr-4"
            />
            <div>
              <h4>Mohamad Haddad</h4>
              <p class="text-neutral-600 text-sm">Managing Partner, SMG</p>
            </div>
          </div>
          <p class="text-neutral-700 mb-4">
            "Their team's blend of AI expertise and human creativity helped us
            launch our MVP three weeks ahead of schedule. The cost savings were
            substantial."
          </p>
          <div class="flex">
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
          </div>
        </div>
        <div class="bg-neutral-50 p-8 rounded-lg">
          <div class="flex items-center mb-6">
            <img
              src="https://d22m7af16es7fs.cloudfront.net/taleb.jpeg"
              alt="Client"
              class="w-12 h-12 rounded-full mr-4"
            />
            <div>
              <h4>Ali Taleb</h4>
              <p class="text-neutral-600 text-sm">Product Director, Fawtal</p>
            </div>
          </div>
          <p class="text-neutral-700 mb-4">
            "The quality of work from NovoProg was outstanding. Their project
            management ensured smooth communication while their development team
            delivered excellent code."
          </p>
          <div class="flex">
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
            <i class="fa-solid fa-star text-neutral-800"></i>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing Section -->

  <!-- FAQ Section -->
  <section id="faq" class="py-20 bg-gray-50">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-16">
        <h2 class="text-3xl md:text-4xl font-bold mb-4">
          Frequently Asked Questions
        </h2>
        <p class="text-xl text-gray-600 max-w-3xl mx-auto">
          Answers to common questions about our services
        </p>
      </div>

      <div
        class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-8 max-w-6xl mx-auto"
      >
        <!-- FAQ Item 1 -->
        <div id="faq-item-1" class="border-b border-gray-200 pb-6">
          <button
            class="accordion-toggle flex justify-between items-center w-full text-left"
          >
            <h3 class="text-xl font-semibold">
              How do AI agents work alongside your team?
            </h3>
            <i class="fa-solid fa-plus text-primary transition-transform"></i>
          </button>
          <div class="accordion-content mt-4">
            <p class="text-gray-600">
              Our AI agents handle repetitive tasks, data analysis, and initial
              drafts, while our human experts focus on strategy, complex
              problem-solving, and quality assurance. This hybrid approach
              combines the efficiency of AI with the creativity and judgment of
              experienced professionals.
            </p>
          </div>
        </div>

        <!-- FAQ Item 2 -->
        <div id="faq-item-2" class="border-b border-gray-200 pb-6">
          <button
            class="accordion-toggle flex justify-between items-center w-full text-left"
          >
            <h3 class="text-xl font-semibold">What's your engagement model?</h3>
            <i class="fa-solid fa-plus text-primary transition-transform"></i>
          </button>
          <div class="accordion-content mt-4">
            <p class="text-gray-600">
              We offer both project-based and subscription models. For one-time
              projects, we provide detailed scoping and fixed pricing. Our
              subscription plans include ongoing development, maintenance, and
              consulting hours that can be used flexibly across your
              initiatives.
            </p>
          </div>
        </div>

        <!-- FAQ Item 3 -->
        <div id="faq-item-3" class="border-b border-gray-200 pb-6">
          <button
            class="accordion-toggle flex justify-between items-center w-full text-left"
          >
            <h3 class="text-xl font-semibold">
              How quickly can I get started?
            </h3>
            <i class="fa-solid fa-plus text-primary transition-transform"></i>
          </button>
          <div class="accordion-content mt-4">
            <p class="text-gray-600">
              For most clients, we can begin the discovery phase within 1-2
              weeks of initial contact. Our AI-assisted approach accelerates the
              initial design and prototyping phases, allowing us to deliver
              value faster than traditional consulting firms.
            </p>
          </div>
        </div>

        <!-- FAQ Item 4 -->
        <div id="faq-item-4" class="border-b border-gray-200 pb-6">
          <button
            class="accordion-toggle flex justify-between items-center w-full text-left"
          >
            <h3 class="text-xl font-semibold">
              Do you offer custom pricing for specific needs?
            </h3>
            <i class="fa-solid fa-plus text-primary transition-transform"></i>
          </button>
          <div class="accordion-content mt-4">
            <p class="text-gray-600">
              Yes, we understand that every business has unique requirements. We
              offer customized pricing based on project scope, timeline, and
              specific technologies involved. Contact us for a personalized
              quote tailored to your specific needs.
            </p>
          </div>
        </div>

        <!-- FAQ Item 5 -->
        <div id="faq-item-5" class="border-b border-gray-200 pb-6">
          <button
            class="accordion-toggle flex justify-between items-center w-full text-left"
          >
            <h3 class="text-xl font-semibold">
              How do you ensure data security?
            </h3>
            <i class="fa-solid fa-plus text-primary transition-transform"></i>
          </button>
          <div class="accordion-content mt-4">
            <p class="text-gray-600">
              We implement industry-standard security protocols including
              encryption, secure access controls, and regular security audits.
              All client data is handled according to strict confidentiality
              agreements, and we comply with relevant regulations such as GDPR
              and CCPA.
            </p>
          </div>
        </div>

        <!-- FAQ Item 6 -->
        <div id="faq-item-6" class="border-b border-gray-200 pb-6">
          <button
            class="accordion-toggle flex justify-between items-center w-full text-left"
          >
            <h3 class="text-xl font-semibold">
              What technologies do you specialize in?
            </h3>
            <i class="fa-solid fa-plus text-primary transition-transform"></i>
          </button>
          <div class="accordion-content mt-4">
            <p class="text-gray-600">
              We have expertise in a wide range of technologies including cloud
              platforms (AWS, Azure, GCP), programming languages (Python,
              JavaScript, Java), AI/ML frameworks (TensorFlow, PyTorch), and
              database systems (SQL, NoSQL). Our team stays current with
              emerging technologies to provide cutting-edge solutions.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20 bg-dark text-white">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-16">
        <h2 class="text-3xl md:text-4xl font-bold mb-4">Get In Touch</h2>
        <p class="text-xl text-gray-800 max-w-3xl mx-auto">
          Ready to accelerate your business with intelligent solutions?
        </p>
      </div>

      <div class="flex flex-col md:flex-row gap-12 max-w-6xl mx-auto">
        <!-- Contact Form -->
        <div class="md:w-1/2">
          <form
            @submit.prevent="handleSubmit"
            id="contact-form"
            class="space-y-6"
          >
            <div>
              <label for="name" class="block mb-2 font-medium">Name</label>
              <input
                type="text"
                id="name"
                v-model="form.name"
                class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-md focus:outline-none focus:ring-2 focus:ring-primary text-white"
                placeholder="Your name"
                required=""
              />
            </div>
            <div>
              <label for="email" class="block mb-2 font-medium">Email</label>
              <input
                type="email"
                id="email"
                v-model="form.email"
                class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-md focus:outline-none focus:ring-2 focus:ring-primary text-white"
                placeholder="Your email"
                required=""
              />
            </div>
            <div>
              <label for="message" class="block mb-2 font-medium"
                >Message</label
              >
              <textarea
                id="message"
                rows="5"
                v-model="form.message"
                class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-md focus:outline-none focus:ring-2 focus:ring-primary text-white"
                placeholder="How can we help you?"
                required=""
              ></textarea>
            </div>
            <button
              type="submit"
              class="w-full py-3 px-6 bg-primary text-white font-medium rounded-md hover:bg-indigo-600 transition-colors"
            >
              Send Message
            </button>
          </form>
        </div>

        <!-- Contact Information -->
        <div class="md:w-1/2">
          <div class="space-y-8">
            <div>
              <h3 class="text-xl font-bold mb-4">Contact Information</h3>
              <p class="text-gray-800 mb-6">
                Reach out to us for a free consultation or to learn more about
                our services.
              </p>
            </div>

            <div class="space-y-4">
              <div class="flex items-start">
                <div class="text-primary mr-4 mt-1">
                  <i class="fa-solid fa-location-dot"></i>
                </div>
                <div>
                  <h4 class="font-medium">Address</h4>
                  <p class="text-gray-800">
                    123 Innovation Drive, Tech Park<br />San Francisco, CA 94103
                  </p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="text-primary mr-4 mt-1">
                  <i class="fa-solid fa-phone"></i>
                </div>
                <div>
                  <h4 class="font-medium">Phone</h4>
                  <p class="text-gray-800">+1 (555) 123-4567</p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="text-primary mr-4 mt-1">
                  <i class="fa-solid fa-envelope"></i>
                </div>
                <div>
                  <h4 class="font-medium">Email</h4>
                  <p class="text-gray-800">info@novoprog.com</p>
                </div>
              </div>
            </div>

            <div>
              <h4 class="font-medium mb-4">Follow Us</h4>
              <div class="flex space-x-4">
                <span
                  class="text-gray-300 hover:text-white transition-colors cursor-pointer"
                >
                  <i class="fa-brands fa-linkedin text-2xl"></i>
                </span>
                <span
                  class="text-gray-300 hover:text-white transition-colors cursor-pointer"
                >
                  <i class="fa-brands fa-twitter text-2xl"></i>
                </span>
                <span
                  class="text-gray-300 hover:text-white transition-colors cursor-pointer"
                >
                  <i class="fa-brands fa-facebook text-2xl"></i>
                </span>
                <span
                  class="text-gray-300 hover:text-white transition-colors cursor-pointer"
                >
                  <i class="fa-brands fa-instagram text-2xl"></i>
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer id="footer" class="bg-gray-900 text-gray-400 py-8">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex flex-col md:flex-row justify-between items-center">
        <div class="mb-4 md:mb-0">
          <p>© 2023 NovoProg. All rights reserved.</p>
        </div>
        <div class="flex space-x-6">
          <span class="hover:text-white transition-colors cursor-pointer"
            >Privacy Policy</span
          >
          <span class="hover:text-white transition-colors cursor-pointer"
            >Terms of Service</span
          >
          <span class="hover:text-white transition-colors cursor-pointer"
            >Sitemap</span
          >
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
import { ref, onMounted } from "vue";

const isDark = ref(false);
const form = ref({
  name: "",
  email: "",
  company: "",
  message: "",
});

const isSubmitting = ref(false);
const submitStatus = ref({
  success: false,
  message: "",
});

const videoPlayer = ref(null);
const videoPlaceholder = ref(null);
const isVideoPlaying = ref(false);

const playVideo = () => {
  if (videoPlayer.value) {
    if (videoPlayer.value.paused) {
      videoPlayer.value.play();
      isVideoPlaying.value = true;
    } else {
      videoPlayer.value.pause();
      isVideoPlaying.value = false;
    }
  }
};

const toggleDarkMode = () => {
  isDark.value = !isDark.value;
  document.documentElement.classList.toggle("dark");
};

const handleSubmit = async () => {
  try {
    isSubmitting.value = true;
    submitStatus.value = { success: false, message: "" };

    // Validate form
    if (!form.value.name || !form.value.email || !form.value.message) {
      throw new Error("Please fill in all required fields");
    }

    // Send form data to API
    const response = await $fetch("/api/contact", {
      method: "POST",
      body: form.value,
    });

    if (response.status === 200) {
      submitStatus.value = {
        success: true,
        message: "Thank you for your message! We will get back to you soon.",
      };
      // Reset form
      form.value = {
        name: "",
        email: "",
        company: "",
        message: "",
      };
    } else {
      throw new Error(response.message || "Failed to send message");
    }
  } catch (error) {
    submitStatus.value = {
      success: false,
      message: error.message || "Something went wrong. Please try again.",
    };
  } finally {
    isSubmitting.value = false;
  }
};

// Video player functionality
onMounted(() => {
  if (videoPlayer.value) {
    videoPlayer.value.addEventListener("play", () => {
      isVideoPlaying.value = true;
    });

    videoPlayer.value.addEventListener("pause", () => {
      isVideoPlaying.value = false;
    });

    videoPlayer.value.addEventListener("ended", () => {
      isVideoPlaying.value = false;
    });
  }
  const mobileMenuButton = document.getElementById("mobile-menu-button");
  const mobileMenu = document.getElementById("mobile-menu");

  mobileMenuButton.addEventListener("click", () => {
    mobileMenu.classList.toggle("hidden");
    mobileMenuButton.innerHTML = mobileMenu.classList.contains("hidden")
      ? '&lt;i class="fa-solid fa-bars text-2xl"&gt;&lt;/i&gt;'
      : '&lt;i class="fa-solid fa-times text-2xl"&gt;&lt;/i&gt;';
  });

  // Sticky Header
  const header = document.getElementById("header");

  window.addEventListener("scroll", () => {
    if (window.scrollY > 100) {
      header.classList.add("py-2");
      header.classList.add("shadow-md");
    } else {
      header.classList.remove("py-2");
      header.classList.remove("shadow-md");
    }
  });

  // Smooth Scrolling for Navigation Links
  document.querySelectorAll('a[href^="#"]').forEach((anchor) => {
    anchor.addEventListener("click", function (e) {
      e.preventDefault();

      // Close mobile menu if open
      if (!mobileMenu.classList.contains("hidden")) {
        mobileMenu.classList.add("hidden");
        mobileMenuButton.innerHTML =
          '&lt;i class="fa-solid fa-bars text-2xl"&gt;&lt;/i&gt;';
      }

      const target = document.querySelector(this.getAttribute("href"));
      if (target) {
        window.scrollTo({
          top: target.offsetTop - 80,
          behavior: "smooth",
        });
      }
    });
  });

  // FAQ Accordion
  const accordionToggles = document.querySelectorAll(".accordion-toggle");

  accordionToggles.forEach((toggle) => {
    toggle.addEventListener("click", () => {
      const content = toggle.nextElementSibling;
      const icon = toggle.querySelector("i");

      content.classList.toggle("active");

      if (content.classList.contains("active")) {
        icon.classList.remove("fa-plus");
        icon.classList.add("fa-minus");
      } else {
        icon.classList.remove("fa-minus");
        icon.classList.add("fa-plus");
      }
    });
  });

  // Form Submission
  const contactForm = document.getElementById("contact-form");

  contactForm.addEventListener("submit", (e) => {
    e.preventDefault();
    // Here you would normally handle the form submission with AJAX
    alert("Thank you for your message! We will get back to you soon.");
    contactForm.reset();
  });
});
// Mobile Menu Toggle
</script>
