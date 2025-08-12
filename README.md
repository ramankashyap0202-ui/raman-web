HeeralLearningClassesLandingPage() {

  const whatsappNumber = "+91XXXXXXXXXX"; // Replace with your WhatsApp number here

  const whatsappLink = `https://wa.me/${whatsappNumber.replace(/\D/g, "")}`;


  return (

    <div className="min-h-screen bg-gray-50 p-6 flex items-center justify-center">

      <main className="max-w-3xl bg-white rounded-xl shadow-lg p-8">

        <header>

          <h1 className="text-3xl font-bold mb-6 text-center">

            Heeral Learning Classes — Online Tuition for Classes 1 to 8

          </h1>

        </header>


        <section>

          <p className="mb-4 text-gray-700 leading-relaxed">

            Welcome to Heeral Learning Classes, where personalized online tuition meets affordable pricing and proven results. Designed specifically for students from Class 1 to Class 8, our classes cover all core school subjects, including Maths, Science, English, Social Studies, and Hindi (if required). Our goal is simple: to make learning clear, engaging, and effective for every student.

          </p>

        </section>


        <section>

          <h2 className="text-xl font-semibold mb-3">Why Choose Heeral Learning Classes?</h2>

          <ul className="list-disc list-inside text-gray-700 mb-6 space-y-2">

            <li>

              <strong>Qualified & Caring Teacher:</strong> I hold an M.A. and B.Ed. degree with specialization in English and Social Studies. With years of teaching experience, I focus on helping each student build strong foundations and develop confidence.

            </li>

            <li>

              <strong>All Subjects Covered:</strong> Tailored lessons in Maths, Science, English, Social Studies, and Hindi, matched to each child’s grade and pace.

            </li>

            <li>

              <strong>Affordable Pricing:</strong> Only ₹500 per month. Choose group or one-to-one classes as per your needs.

            </li>

            <li>

              <strong>Flexible Online Mode:</strong> Classes held on Zoom or Google Meet for convenience and safety.

            </li>

          </ul>

        </section>


        <section>

          <h2 className="text-xl font-semibold mb-3">What You Can Expect</h2>

          <ul className="list-disc list-inside text-gray-700 mb-6 space-y-2">

            <li>Personalized attention starting with a diagnostic assessment.</li>

            <li>Clear lessons paced to student understanding and interactive discussions.</li>

            <li>Regular homework with monthly progress updates for parents.</li>

            <li>Exam-focused revision tailored to school syllabus.</li>

          </ul>

        </section>


        <section>

          <h2 className="text-xl font-semibold mb-3">Sample Lesson Plan (Grades 3–5)</h2>

          <ul className="list-disc list-inside text-gray-700 mb-6 space-y-2">

            <li><strong>Week 1:</strong> Diagnostic assessment, English reading comprehension, and Maths number sense.</li>

            <li><strong>Week 2:</strong> Science concepts of living vs non-living, English grammar basics, and Maths word problems.</li>

            <li><strong>Weeks 3 & 4:</strong> Social studies on local community, practice tests, homework review, and personalized tips.</li>

          </ul>

        </section>


        <footer className="text-center">

          <a

            href={whatsappLink}

            target="_blank"

            rel="noopener noreferrer"

            className="inline-block bg-green-600 hover:bg-green-700 text-white font-semibold py-3 px-6 rounded-lg transition"

          >

            Contact on WhatsApp (₹500 / month)

          </a>

        </footer>

      </main>

    </div>

  );

}

