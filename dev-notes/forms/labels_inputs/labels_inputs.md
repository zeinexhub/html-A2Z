<h1 align="center">Labels and Inputs</h1>

> HTML-এ ফর্ম তৈরি করার জন্য labels এবং inputs হলো মৌলিক উপাদান। Label একটি বর্ণনামূলক টেক্সট প্রদান করে, যা ব্যবহারকারীকে জানায় সংশ্লিষ্ট input ফিল্ডে কী তথ্য দিতে হবে। অন্যদিকে, input এলিমেন্ট হলো ইন্টারঅ্যাকটিভ কন্ট্রোল, যেখানে ব্যবহারকারী তথ্য প্রবেশ করাতে পারে। যেমন: টেক্সট, সংখ্যা, তারিখ, অথবা বিভিন্ন অপশনের মধ্যে নির্বাচন। এই দুটি একসাথে কাজ করে একটি ব্যবহারবান্ধব এবং অ্যাক্সেসিবল ফর্ম অভিজ্ঞতা তৈরি করে।

### • Attributes

> `type` ইনপুটের ধরন নির্ধারণ করে। এটি বলে দেয় ইনপুটটি কী ধরনের ডেটা নেবে এবং ব্রাউজার কীভাবে সেটি আচরণ করবে। `type` না দিলে default হয় text.

```html
<input type="text" />
<input type="password" />
<input type="email" />
<input type="number" />
<input type="submit" />
```

> `id` একটি এলিমেন্টকে ইউনিকভাবে চিহ্নিত করে। CSS দিয়ে স্টাইল করার জন্য, JavaScript দিয়ে নির্দিষ্ট এলিমেন্ট ধরার জন্য, `<label>` কে ইনপুটের সাথে যুক্ত করার জন্য ব্যবহৃত হয়। `id` server এ যায় না।

```html
<label for="username">Username </label>
<input type="text" id="username" />
```

```js
document.getElementById("username").value;
```

> `name` হচ্ছে ডেটার নাম। যা Form Submission এর জন্য সবচেয়ে গুরুত্বপূর্ণ। এটি সার্ভারে ডেটা পাঠানোর সময় key হিসেবে ব্যবহৃত হয়। `name` না থাকলে form data পাঠানো হয় না।

```html
<label for="username">Username</label>
<input type="text" id="username" name="username" />
```
