### ডেটাফ্রেম পরিবর্তন করা

অনেক সময় ডেটাসেটে ডেটা মিসিং থাকতে পারে। আমাদের সেই মিসিং ডেটাও হ্যান্ডেল করতে হবে। হ্যাঁ, হয়ত আমরা হারানো ডেটা পাব না, তবে প্রয়োজনীয় ব্যবস্থা না নিলে প্রোগ্রাম ক্র্যাশ করতে পারে।


#### কোন কোন Column বাদ দিতে হবে?

* যেগুলো ব্যবহার করা হবে না
* কলাম আছে কিন্তু ডেটা নাই
* একই কলাম যদি একাধিকবার থাকে, তাহলে একটা রেখে বাকিগুল‌ো মুছে দিতে হবে