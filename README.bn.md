## To read this document in english [click here](https://github.com/hissain/CoronaTracker/blob/dev/README.md) ##

### প্রকল্প ###
এই প্রকল্পটি কোনও কোভিড-১৯ সংক্রামিত রোগীর জন্য গত ১৪ দিনের মধ্যে ঘনিষ্ঠ পরিচিতিগুলি ট্র্যাক করার জন্য অ্যাপ্লিকেশন তৈরি করবে

### পটভূমি ###
কোভিড-১৯ বিশ্বব্যাপী আলোচিত, যা ইতিমধ্যে মহামারী হিসাবে ঘোষিত হয়েছে এর কারণে মানবতা সংকটে রয়েছে। বিশ্বব্যাপী এই সংকটের মোকাবেলার এবং সমাধান করার জন্য আমাদের আমাদের প্রযুক্তিগত উদ্ভাবনের এবং ফলাফল অর্জনের এটি অত্যন্ত সময়। আক্রান্ত দেশগুলির যে কোনও সরকারের পক্ষে সবচেয়ে কঠিন চ্যালেঞ্জগুলির মধ্যে একটি হলো সংক্রমণের বক্ররেখাকে সমতল করা। এদের মধ্যে আক্রান্ত রোগীদের প্রাথমিক সনাক্তকরণ বক্রাকার সমতল করার জন্য সবচেয়ে গুরুত্বপূর্ণ কাজ। যখন কোন রোগী কোভিড-১৯ সংক্রামিত হিসাবে চিহ্নিত হন, সরকার আক্রান্তের বন্ধুবান্ধব এবং তার পরিবারকে জিজ্ঞাসা করার মতো ম্যানুয়াল প্রক্রিয়াগুলির মাধ্যমে রোগীর ঘনিষ্ঠ যোগাযোগের তথ্য পাওয়ার চেষ্টা করছে। তবে তথ্যের নির্ভুলতা, তথ্য পুনরুদ্ধারের বিলম্ব ইত্যাদির ক্ষেত্রে এই পদ্ধতির অনেক সীমাবদ্ধতা রয়েছে। সীমাবদ্ধ কারণগুলোর কয়েকটি হল,

1. বন্ধু বান্ধব এবং পরিবার থেকে মিথ্যা তথ্য
2. সামাজিক বিব্রততা এড়াতে রোগী এবং পরিবার দ্বারা লুকানো তথ্য
3. রোগীর অজানা বা অনুপস্থিত তথ্য
4. ম্যানুয়াল প্রক্রিয়াগুলির কারণে বিলম্বিত তথ্য

### আইডিয়া: প্রযুক্তি কীভাবে সহায়তা করতে পারে? ###
অল্প সময়ের মধ্যে একটি অ্যাপ্লিকেশন তৈরি করা যেতে পারে যা বেশিরভাগ জনপ্রিয় প্ল্যাটফর্মগুলিতে (অ্যান্ড্রয়েড, আইওএস) চলবে।
নাগরিক দায়িত্বের অংশ হিসাবে বাংলাদেশি সরকারকে তার সমস্ত নাগরিকের জন্য এই অ্যাপ্লিকেশনটি স্থাপনের প্রয়োগ করতে হবে। আরও বিশ্লেষণের পরে মোতায়েনের নীতি এবং কৌশল তৈরি করা যেতে পারে। অপারেটরগুলির মতো, জিপি, রবি, বাংলালিংক সহায়ক হতে পারে। জাতীয় আইডি (এনআইডি) সার্ভারে নিবন্ধকরণের জন্য ব্যবহার করা হবে কারণ এনআইডি ব্যবহার করে সরকার সহজেই নাগরিকদের বিশদ অর্জন করতে পারে। সমস্ত নাগরিকের ঘনিষ্ঠ যোগাযোগের ডেটা সহ সমস্ত অবস্থান একটি কেন্দ্রীয় সার্ভারে সংরক্ষণ করা হবে। অ্যাপ্লিকেশনটি জিপিএস (গ্লোবাল পজিশনিং সিস্টেম) এবং অন্যান্য প্রযুক্তি ব্যবহার করে ব্যবহারকারীর গতিপথ ট্র্যাক করতে এবং ব্যবহারকারীর সমস্ত ঘনিষ্ঠ পরিচিতি সনাক্ত করতে এবং গত কয়েক সপ্তাহ ধরে ইতিহাস (যেমন, ১৪ দিন, কনফিগারযোগ্য) ডেটা সার্ভারে সঞ্চয় করবে।

### আইডিয়া: চিত্রণ ###
প্রকল্পের বৃহৎ পরিসর আর্কিটেকচার [এখানে](https://github.com/hissain/CoronaTracker/blob/dev/architecture/Architecture.md) আলোচনা করা হয়েছে।

![Conceptual Illutration](https://github.com/hissain/CoronaTracker/blob/master/architecture/ctracker-datascheme.png)  

### ব্যবস্থা পরিকল্পনা ###
সামগ্রিকভাবে সিস্টেম নকশা এখানে উপলব্ধ,
<img src="https://github.com/hissain/CoronaTracker/blob/master/architecture/SystemDesign.png" alt="Android Registration"/>

Link: [system design](https://github.com/hissain/CoronaTracker/blob/master/architecture/SystemDesign.png)

### কিভাবে এটা কাজ করে? ###
আমরা বেশিরভাগ সময় জানি আমরা আমাদের স্মার্টফোনগুলি আমাদের সাথে রাখি এমনকি আমরা কথা বলি, হাঁটছি, জমায়েত হব, আহার করি, উত্সবে যোগ দিই এবং এমন কি। যদি করোনট্র্যাকার অ্যাপ্লিকেশনটি দেশের সকল নাগরিকের স্মার্টফোনে আদর্শভাবে ইনস্টল করা থাকে তবে নির্দিষ্ট সময়ের জন্য কোভিড -১৯ পজিটিভ রোগীর ঘনিষ্ঠ যোগাযোগের তথ্য (যেমন ২/৩ ~ ৫/১০ মিনিট, কনফিগারযোগ্য) সহজেই সনাক্ত করা যায় জিপিএস, ব্লুটুথ এবং এনএফসি ডেটার সংমিশ্রণ থেকে এবং সার্ভারে লগইন হয়েছে। সুতরাং, যদি কোনও নাগরিক কোভিড-১৯ ইতিবাচক হিসাবে চিহ্নিত হয়, সরকার অন্যান্য বিশদ তথ্যের (যেমন যোগাযোগের সময়সীমা, দূরত্ব, সময় এবং স্থান) সহ ঘনিষ্ঠ যোগাযোগের সম্পূর্ণ তালিকা পেতে পারে। এগুলি অবশ্যই নিখুঁত হওয়ার যোগ্য প্রার্থীদের চিহ্নিত করার জন্য এবং আরও তাত্ক্ষণিক পরীক্ষার জন্য খুব সঠিক তথ্য উত্পন্ন করবে।

### মূল প্রতিদ্বন্দ্বিতা ###
1. **অ্যাপ্লিকেশন ইনস্টলেশন** - অনেক নাগরিকের কোনও স্মার্টফোন থাকবে না তাই তারা এই প্রকল্পের বাইরে থাকবে। তবে এটি ইস্যু হবে না কারণ নাগরিকদের কমপক্ষে একটি বড় অংশ এই প্রকল্পের আওতায় আসতে পারে।
2. **ব্যবহারকারীর গোপনীয়তা** - ব্যবহারকারী তাদের অবস্থানগুলি ভাগ করতে সম্মত হতে পারে - তবে সরকার মানবিকতার জন্য মোবাইল অপারেশন, নিউজ মিডিয়া, টেলিভিশন, সরকারী ওয়েবসাইটগুলির মাধ্যমে সচেতনতা তৈরি করতে পারে। স্বাস্থ্য বনাম গোপনীয়তার মধ্যে কেউই স্বাস্থ্য ডাট শেয়ার করতে চায় না। তদুপরি, সামাজিক বিশৃঙ্খলা এবং গোপনীয়তার বিষয়টি এড়াতে কেবলমাত্র সরকারী নাগরিকদের কাছে কেবল যোগাযোগের (সমস্ত অবস্থানের তথ্য নয়) প্রবেশাধিকার পড়তে হবে।
3. **গণনা / স্টোরেজ** - অবকাঠামোর অংশ হিসাবে স্টোরেজ করা একটি চ্যালেঞ্জ হবে। তবে আমরা কেবল গত কয়েক দিন অর্থাত্ (১৪ দিনের ডেটা) সার্ভারে কাঁচা ডেটা রাখতে পারি যাতে স্টোরেজটি রৈখিক এবং সহজেই স্কেলেবল হয়। অ্যামাজন / গুগলক্লাউড ইত্যাদির মতো আইএএস সরবরাহকারীর কাছে গণনাটি দ্রুত আউটসোর্স করা যায় etc.
4. **জিপিএস অপ্রতুলতা** - প্রাথমিক প্রস্তাবটি হল জিপিএস ব্যবহার করা যা সঠিকভাবে প্রায় ~৩ মিটারের নিখুঁত থাকে। তবে কোভিড-১৯ এর জন্য নিবিড় যোগাযোগগুলি সনাক্ত করা সম্ভব হবে না। আমরা যদি জিপিএসের সাথে ব্লুটুথ এবং অন্য API বিবেচনা করতে পারি তবে উপযুক্ত অ্যালগরিদম তৈরির পরে সঠিক তথ্য সংরক্ষণাগারভুক্ত করা যেতে পারে।

### অবদানকারীদের নির্দেশিকা ###
1. ব্যাকলোগগুলি এখানে অ্যান্ড্রয়েড, আইওএস এবং সার্ভার বিকাশকারীদের জন্য পাওয়া যাবে [here](https://github.com/hissain/CoronaTracker/projects) । আপনি এখান থেকে একটি কাজ বেছে নিতে এবং কাজ শুরু করতে পারেন। এই [Youtube tutorial video](https://www.youtube.com/watch?v=e3bjQX9jIBk) ইউটিউব টিউটোরিয়াল ভিডিওটি তাজা অবদানকারীদের সহায়তা করতে পারে।
2. আপনি এখানে API এর খসড়া সার্ভার ডেটা স্কিমগুলির বিশিষ্ট আর্কিটেকচারটি ঘুরে দেখতে পারেন। বর্তমান কোডবেস বুঝতে দয়া করে অন্বেষণ করুন যাতে আপনার অবদান রাখা আরও সহজ হয়ে যায়।
3. আপনি যদি ইউআই ডিজাইনের পক্ষে অবদান রাখতে চান তবে আমরা অ্যান্ড্রয়েড এবং আইওএস অ্যাপ্লিকেশন উভয়ের জন্য অর্থবহ লোগো এবং থাম্বগুলির জন্য অপেক্ষা করছি। আপনি লোগো / থাম্ব সেট তৈরি করার পরে আমাদের কাছে অনুরোধ করুন।
4. আমরা ক্যান EC2 এবং RDS এর জন্য সাহায্যকারী সন্ধান করছি। যে কেউ প্রাথমিক অ্যাপ্লিকেশান টি সফল করার জন্য পরিষেবাগুলি ভাগ করে এই অংশটিতে অবদান রাখতে পারে।

### মুল পাতার ছবি ### 
<p>
<img src="https://github.com/hissain/CoronaTracker/blob/master/architecture/Screenshots/Android/Screenshot_Registration.png" alt="Android Registration" width="300"/>

<img src="https://github.com/hissain/CoronaTracker/blob/dev/architecture/Screenshots/iOS/Screenshot_Registration.png" alt="Android Registration" width="245"/>
  
<img src="https://github.com/hissain/CoronaTracker/blob/dev/architecture/Screenshots/iOS/Screenshot_Registration_bn.png" alt="Android Registration" width="245"/>
</p>

### যোগাযোগ ঠিকানা ### 
আপনি এই প্রকল্পে কাজ করতে আগ্রহী হলে আমাকে মেইল করুন এখানে hissain.khan@gmail.com 