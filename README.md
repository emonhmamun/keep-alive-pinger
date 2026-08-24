# Keep-Alive Pinger

24/7 external pinger — prevents sandbox idle/sleep.

## Setup (২ ধাপ)

### ধাপ ১: Workflow ফাইল তৈরি করুন

১. এই লিংকে যান: https://github.com/emonhmamun/keep-alive-pinger/new/main/.github/workflows
২. ফাইলের নাম দিন: `keep-alive.yml`
৩. `keep-alive-workflow.yml` ফাইলের কোড কপি করে পেস্ট করুন
৪. **Commit new file** ক্লিক করুন

### ধাপ ২: Secret যোগ করুন

১. Settings → Secrets → Actions → New secret
২. Name: `PUBLIC_URL`
৩. Value: আপনার প্রজেক্টের URL
৪. Add secret ক্লিক করুন

## প্রাইভেসি নিশ্চয়তা

- ✅ URL লগে কখনো দেখা যায় না
- ✅ সোর্স কোড এই রিপোতে নেই
- ✅ শুধু "✅ ALIVE" বা "❌ DOWN" লগে দেখা যায়
- ✅ Secret এনক্রিপ্টেড (GitHub নিজেও পড়তে পারে না)
