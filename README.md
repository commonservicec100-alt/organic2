<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>OrganicDesh — খেত থেকে আপনার থালি পর্যন্ত</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .star { color: #f59e0b; }
    .card-shadow { box-shadow: 0 6px 18px rgba(15,23,42,0.06); }
  </style>
</head>
<body class="bg-gradient-to-b from-white to-green-50 min-h-screen text-gray-800">
  <!-- Header -->
  <header class="bg-white shadow-sm sticky top-0 z-50">
    <div class="max-w-6xl mx-auto px-4 py-3 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <div class="w-10 h-10 bg-green-600 rounded-full flex items-center justify-center text-white font-bold">OD</div>
        <div>
          <div class="font-bold">OrganicDesh</div>
          <div class="text-xs text-gray-500">Fresh from Farm to Table</div>
        </div>
      </div>
    </div>
  </header>

  <main class="max-w-6xl mx-auto p-4">
    <!-- Hero -->
    <section class="bg-white rounded-xl p-6 shadow flex flex-col md:flex-row items-center gap-6 mt-6">
      <div class="flex-1">
        <h1 class="text-3xl md:text-4xl font-extrabold">OrganicDesh — খেত থেকে আপনার থালি পর্যন্ত</h1>
        <p class="mt-3 text-gray-600">নিরাপদ, ১০০% অর্গানিক সবজি — নিয়মিত ডেলিভারি। Weekly প্যাক-এ নিজের ৫টি নির্বাচন করুন।</p>
      </div>
    </section>

    <!-- Packages -->
    <section id="packages" class="mt-8 grid gap-6 md:grid-cols-2">
      <div class="bg-white rounded-xl p-6 shadow card-shadow">
        <h3 class="text-2xl font-semibold mb-3">আমাদের প্যাকেজ</h3>
        <div class="space-y-6">

          <!-- Regular Pack -->
          <div class="border rounded-lg p-4">
            <div class="flex items-center justify-between">
              <div>
                <div class="text-lg font-semibold">Regular Pack (Fixed — ১০ ধরণের সবজি)</div>
                <div class="text-sm text-gray-600">প্রতিদিন / প্রয়োজন অনুযায়ী ডেলিভারি</div>
              </div>
              <div class="text-green-600 font-bold">Tk. 120/day</div>
            </div>
            <div class="mt-3 text-sm text-gray-700">
              <strong>Regular Pack (10 items):</strong>
              <ul class="list-disc ml-6 mt-2">
                <li>আলু (Potato)</li>
                <li>গাজর (Carrot)</li>
                <li>কমড়া / কুমড়া (Pumpkin / Summer squash)</li>
                <li>বেগুন (Eggplant)</li>
                <li>টমেটো (Tomato)</li>
                <li>লাউ (Bottle gourd)</li>
                <li>পটল (Pointed gourd)</li>
                <li>ঝিঙে (Ridge gourd)</li>
                <li>ঢেঁড়স (Ash gourd / Ridge vegetable)</li>
                <li>শাক (Mixed leafy greens)</li>
              </ul>
            </div>
            <div class="mt-4">
              <button data-plan="regular" class="choosePlan w-full bg-green-600 text-white py-2 rounded">Choose Regular Pack</button>
            </div>
          </div>

          <!-- Weekly Pack: choose 5 -->
          <div class="border rounded-lg p-4">
            <div class="flex items-center justify-between">
              <div>
                <div class="text-lg font-semibold">Weekly Pack (Choose 5 items)</div>
                <div class="text-sm text-gray-600">সাপ্তাহিক প্যাক — আপনার পছন্দের ৫টি সবজি বেছে নিন</div>
              </div>
              <div class="text-green-600 font-bold">Tk. 700/week</div>
            </div>

            <div class="mt-3 text-sm text-gray-700">
              <div class="grid grid-cols-2 md:grid-cols-3 gap-2">
                <!-- list of available vegetables for weekly choice -->
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="weeklyItem" value="আলু" />
                  <span>আলু</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="weeklyItem" value="গাজর" />
                  <span>গাজর</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="weeklyItem" value="কমড়া" />
                  <span>কমড়া</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="weeklyItem" value="বেগুন" />
                  <span>বেগুন</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="weeklyItem" value="টমেটো" />
                  <span>টমেটো</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="weeklyItem" value="লাউ" />
                  <span>লাউ</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="weeklyItem" value="পটল" />
                  <span>পটল</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="weeklyItem" value="ঝিঙে" />
                  <span>ঝিঙে</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="weeklyItem" value="ঢেঁড়স" />
                  <span>ঢেঁড়স</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="weeklyItem" value="শাক" />
                  <span>শাক (Leafy)</span>
                </label>
              </div>

              <div class="mt-3">
                <div class="text-xs text-gray-500">* দয়া করে সর্বোচ্চ ৫টি আইটেম নির্বাচন করুন</div>
                <button id="chooseWeekly" class="mt-2 w-full bg-green-600 text-white py-2 rounded">Choose Weekly Pack (Confirm Selection)</button>
                <div id="weeklyMsg" class="mt-2"></div>
              </div>
            </div>
          </div>

          <!-- Monthly Pack: add-ons -->
          <div class="border rounded-lg p-4">
            <div class="flex items-center justify-between">
              <div>
                <div class="text-lg font-semibold">Monthly Pack (Base + Add-ons)</div>
                <div class="text-sm text-gray-600">৩০ দিনের সাবস্ক্রিপশন — নিচের অ্যাড-অন যোগ করতে পারেন</div>
              </div>
              <div class="text-green-600 font-bold">Tk. 2700/month</div>
            </div>

            <div class="mt-3 text-sm text-gray-700">
              <div class="grid grid-cols-1 md:grid-cols-2 gap-2">
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="monthlyAddon" value="ডিম (12pcs/week)" />
                  <span>ডিম (12pcs/week)</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="monthlyAddon" value="দুধ (5L/week)" />
                  <span>দুধ (5L/week)</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="monthlyAddon" value="মসলা প্যাক" />
                  <span>অর্গানিক মসলা প্যাক</span>
                </label>
                <label class="flex items-center gap-2 p-2 border rounded">
                  <input type="checkbox" class="monthlyAddon" value="হানি (250g)" />
                  <span>অর্গানিক হানি (250g)</span>
                </label>
              </div>

              <div class="mt-3">
                <button id="chooseMonthly" class="w-full bg-green-600 text-white py-2 rounded">Choose Monthly Pack (Confirm Add-ons)</button>
                <div id="monthlyMsg" class="mt-2"></div>
              </div>
            </div>
          </div>

        </div>
      </div>

      <!-- Right column: Subscribe form + Referral + Customer Datastore -->
      <div class="bg-white rounded-xl p-6 shadow card-shadow flex flex-col gap-4">
        <div>
          <h4 class="text-xl font-semibold">Sign Up & Subscribe</h4>
          <p class="text-sm text-gray-600">পছন্দের প্যাক নির্বাচন করে নিচের ফর্ম পূরণ করুন — আমরা কন্টিনিউ করে ডেলিভারি শুরু করবো।</p>
        </div>

        <div>
          <form id="subscribeForm" class="space-y-3">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-2">
              <input id="name" required class="border p-2 rounded" placeholder="নাম" />
              <input id="phone" required class="border p-2 rounded" placeholder="ফোন" />
            </div>

            <input id="email" class="border p-2 rounded w-full" placeholder="ইমেইল (ঐচ্ছিক)" />
            <input id="address" class="border p-2 rounded w-full" placeholder="ডেলিভারি ঠিকানা" />

            <div>
              <label class="text-sm text-gray-600">Selected Plan:</label>
              <input id="selectedPlan" class="border p-2 rounded w-full bg-gray-50" readonly placeholder="Select a plan above" />
            </div>

            <div>
              <label class="text-sm text-gray-600">Selected Items / Add-ons:</label>
              <textarea id="selectedItems" class="border p-2 rounded w-full bg-gray-50" readonly rows="2" placeholder="Your selections will appear here"></textarea>
            </div>

            <div class="flex gap-2">
              <input id="ref" class="border p-2 rounded flex-1" placeholder="Referral code (optional)" />
              <button type="submit" class="bg-green-600 text-white px-4 py-2 rounded">Subscribe</button>
            </div>
          </form>

          <div id="msg" class="mt-3"></div>
        </div>

        <div>
          <h4 class="text-lg font-semibold">Referral System</h4>
          <div class="mt-2 p-3 bg-gray-50 rounded border">
            <div class="text-sm">Your referral code:</div>
            <div id="refCode" class="font-medium mt-1">—</div>
            <div class="text-xs text-gray-500 mt-1">Share this link to earn credit</div>
            <div class="mt-2 flex gap-2">
              <input id="refLink" class="border p-2 rounded flex-1 text-sm" readonly />
              <button id="copyRef" class="bg-green-600 text-white px-3 py-1 rounded">Copy</button>
            </div>
            <div class="text-xs text-gray-500 mt-2">Reward: Tk.100 credit when referred user completes first paid order.</div>
          </div>
        </div>

        <div>
          <h4 class="text-lg font-semibold">Customer Datastore (Mock)</h4>
          <div class="text-sm text-gray-600">মোট গ্রাহক: <span id="customerCount">0</span></div>
          <div id="customerList" class="mt-3 max-h-40 overflow-auto border rounded p-2 bg-gray-50"></div>
        </div>

      </div>
    </section>

    <!-- How it works -->
    <section id="how" class="mt-8 bg-white rounded-xl p-6 shadow card-shadow">
      <h3 class="text-2xl font-semibold mb-3">কিভাবে কাজ করে</h3>
      <div class="grid md:grid-cols-3 gap-4">
        <div class="p-4 bg-gray-50 rounded">
          <div class="font-semibold">1. চুক্তিবদ্ধ কৃষক</div>
          <div class="text-sm text-gray-600 mt-2">স্থানীয় অর্গানিক কৃষকের কাছ থেকে সরাসরি সংগ্রহ।</div>
        </div>
        <div class="p-4 bg-gray-50 rounded">
          <div class="font-semibold">2. প্যাক & কোয়ালিটি</div>
          <div class="text-sm text-gray-600 mt-2">প্রতিটি প্যাকে কোয়ালিটি চেক এবং স্যানিটাইজেশন।</div>
        </div>
        <div class="p-4 bg-gray-50 rounded">
          <div class="font-semibold">3. ডোরস্টেপ ডেলিভারি</div>
          <div class="text-sm text-gray-600 mt-2">নির্ধারিত সময়ে আপনার বাড়িতে ডেলিভারি।</div>
        </div>
      </div>
    </section>

  </main>

  <footer class="bg-white border-t mt-6">
    <div class="max-w-6xl mx-auto p-6 text-sm text-gray-600 flex justify-between">
      <div>© <span id="curYear"></span> OrganicDesh — All rights reserved</div>
      <div>Made with ♥ for healthy homes</div>
    </div>
  </footer>

  <!-- JS: Interactivity & localStorage mock -->
  <script>
    // Helpers
    const el = id => document.getElementById(id);
    const qAll = sel => document.querySelectorAll(sel);

    // Year
    el('curYear').innerText = new Date().getFullYear();

    // Local datastore keys
    const CUSTOMER_KEY = 'od_customers_v2';
    let customers = JSON.parse(localStorage.getItem(CUSTOMER_KEY) || '[]');

    // Referral code for this session (owner demo)
    let myCode = localStorage.getItem('od_my_ref_v2');
    if (!myCode) {
      myCode = 'OD-' + Math.random().toString(36).slice(2,7).toUpperCase();
      localStorage.setItem('od_my_ref_v2', myCode);
    }
    el('refCode').innerText = myCode;
    el('refLink').value = location.origin + location.pathname + '?ref=' + myCode;
    el('copyRef').addEventListener('click', ()=> {
      el('refLink').select();
      navigator.clipboard.writeText(el('refLink').value).then(()=> alert('Referral link copied'));
    });

    // Plan selection handlers
    qAll('.choosePlan').forEach(btn => {
      btn.addEventListener('click', e => {
        const plan = e.target.dataset.plan;
        el('selectedPlan').value = plan === 'regular' ? 'Regular Pack (Daily)' : plan;
        // Regular pack items auto-filled
        if (plan === 'regular') {
          el('selectedItems').value = 'আলু, গাজর, কমড়া, বেগুন, টমেটো, লাউ, পটল, ঝিঙে, ঢেঁড়স, শাক';
        } else {
          el('selectedItems').value = '';
        }
        window.scrollTo({top: el('subscribeForm').offsetTop - 80, behavior:'smooth'});
      });
    });

    // Weekly selection: limit to 5
    const weeklyCheckboxes = Array.from(qAll('.weeklyItem'));
    el('chooseWeekly').addEventListener('click', ()=> {
      const checked = weeklyCheckboxes.filter(cb => cb.checked).map(cb => cb.value);
      if (checked.length === 0) {
        el('weeklyMsg').innerHTML = '<div class="text-red-600 text-sm">কমপক্ষে ১টি নির্বাচন করুন।</div>';
        return;
      }
      if (checked.length > 5) {
        el('weeklyMsg').innerHTML = '<div class="text-red-600 text-sm">সর্বোচ্চ ৫টি নির্বাচন করতে পারবেন।</div>';
        return;
      }
      el('selectedPlan').value = 'Weekly Pack';
      el('selectedItems').value = checked.join(', ');
      el('weeklyMsg').innerHTML = '<div class="text-green-700 text-sm">Weekly নির্বাচন আপডেট হয়েছে। সাবস্ক্রাইব ফর্ম পূরণ করুন।</div>';
      window.scrollTo({top: el('subscribeForm').offsetTop - 80, behavior:'smooth'});
    });

    // Monthly add-ons selection
    el('chooseMonthly').addEventListener('click', ()=> {
      const addons = Array.from(qAll('.monthlyAddon')).filter(cb => cb.checked).map(cb => cb.value);
      el('selectedPlan').value = 'Monthly Pack';
      el('selectedItems').value = addons.length ? addons.join(', ') : 'No add-ons';
      el('monthlyMsg').innerHTML = '<div class="text-green-700 text-sm">Monthly selections saved. সাবস্ক্রাইব ফর্ম পূরণ করুন।</div>';
      window.scrollTo({top: el('subscribeForm').offsetTop - 80, behavior:'smooth'});
    });

    // Subscribe form submit
    el('subscribeForm').addEventListener('submit', (ev) => {
      ev.preventDefault();
      const name = el('name').value.trim();
      const phone = el('phone').value.trim();
      const email = el('email').value.trim();
      const address = el('address').value.trim();
      const plan = el('selectedPlan').value || 'Not selected';
      const items = el('selectedItems').value || '';
      const referred_by = el('ref').value.trim() || null;

      if (!name || !phone) { showMsg('নাম ও ফোন দিতে হবে', 'error'); return; }
      if (plan === '' || plan === 'Not selected') { showMsg('অনুগ্রহ করে একটি প্যাক নির্বাচন করুন', 'error'); return; }

      // create customer mock
      const referral_code = (name.replace(/[^a-zA-Z]/g,'').slice(0,4).toUpperCase() || 'OD') + '-' + Math.random().toString(36).slice(2,6).toUpperCase();
      const newCustomer = {
        id: Date.now(),
        name, phone, email, address, referral_code, referred_by, plan, items, created_at: new Date().toISOString()
      };
      customers.unshift(newCustomer);
      localStorage.setItem(CUSTOMER_KEY, JSON.stringify(customers));
      renderCustomers();
      showMsg(`স্বাগতম ${name}! সাবস্ক্রিপশন রেজিস্টার হয়েছে. আপনার রেফারেল কোড: ${referral_code}`, 'success');

      // reset minimal form fields (keep ref if present)
      el('name').value = ''; el('phone').value = ''; el('email').value = ''; el('address').value = '';
      el('selectedPlan').value = ''; el('selectedItems').value = '';
      el('ref').value = '';
    });

    function showMsg(txt, type='success') {
      const box = el('msg');
      box.innerHTML = `<div class="${type==='success' ? 'bg-green-100 text-green-800' : 'bg-red-100 text-red-800'} p-3 rounded">${txt}</div>`;
      setTimeout(()=> box.innerHTML = '', 6000);
    }

    // render customer list
    function renderCustomers() {
      el('customerCount').innerText = customers.length;
      const container = el('customerList');
      container.innerHTML = '';
      if (!customers.length) {
        container.innerHTML = '<div class="text-gray-500">কোনো গ্রাহক নেই</div>';
        return;
      }
      customers.forEach(c => {
        const d = document.createElement('div');
        d.className = 'p-2 border-b last:border-b-0';
        d.innerHTML = `<div class="text-sm font-medium">${escapeHtml(c.name)} <span class="text-xs text-gray-500">(${escapeHtml(c.phone)})</span></div>
          <div class="text-xs text-gray-500">Plan: ${escapeHtml(c.plan)} | Items: ${escapeHtml(c.items || '')}</div>
          <div class="text-xs text-gray-400">Code: ${escapeHtml(c.referral_code)} ${c.referred_by ? `(referred by ${escapeHtml(c.referred_by)})` : ''}</div>`;
        container.appendChild(d);
      });
    }

    function escapeHtml(s=''){ return String(s).replace(/[&<>"']/g, m => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[m])); }

    // initialize
    renderCustomers();

    // pre-fill referral if present in URL
    (function handleQueryRef(){
      try {
        const url = new URL(location.href);
        const ref = url.searchParams.get('ref');
        if (ref) el('ref').value = ref;
      } catch(e){}
    })();

  </script>
</body>
</html>
# organic2
