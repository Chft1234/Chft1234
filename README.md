- 👋 Hi, I’m @Chft1234
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Chft1234/Chft1234 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at #! / data / data / com.termux / files / usr / bin / bash
صافي
صدى صوت "
    + - + - + - + - + - + - + - + - + - + - + + - + - + + - + - + - + - + - + - +
    | M | e | t | a | s | p | l | o | i | t | | ط | ن | | T | e | r | m | u | x |
    + - + - + - + - + - + - + - + - + - + - + + - + - + + - + - + - + - + - + - +
            + - + - + + - + - + - + - + - + - + - + - + - + - +
            | ب | ذ | | G | u | s | h | m | a | z | u | k | o |
            + - + - + + - + - + - + - + - + - + - + - + - + - +
"

المركز() {
  عرض المدى = $ (حجم ثابت | قطع -d "" -f2)
  المساحة المتروكة = "$ (printf '٪ 0.1s' = {1..500})"
  printf '٪ *. * s٪ s٪ *. * s \ n' 0 "$ (((termwidth-2 - $ {# 1}) / 2))" "$ padding" "$ 1" 0 "$ (( (termwidth-1 - $ {# 1}) / 2)) "" $ padding "
}

# تحميل الدوار
مركز "جارٍ التحميل ..."
source <(echo "c3Bpbm5lcj0oICd8JyAnLycgJy0nICdcJyApOwoKY291bnQoKXsKICBzcGluICYKICBwaWQ9JCEKICBmb3IgaSBpbiBgc2VxIDEgMTBgCiAgZG8KICAgIHNsZWVwIDE7CiAgZG9uZQoKICBraWxsICRwaWQgIAp9CgpzcGluKCl7CiAgd2hpbGUgWyAxIF0KICBkbyAKICAgIGZvciBpIGluICR7c3Bpbm5lcltAXX07IAogICAgZG8gCiAgICAgIGVjaG8gLW5lICJcciRpIjsKICAgICAgc2xlZXAgMC4yOwogICAgZG9uZTsKICBkb25lCn0KCmNvdW50" | base64 -d)

صدى صوت
مركز "*** تثبيت التبعيات ..."

## إزالة المستودعات لا تعمل
rm $ PREFIX / etc / apt / sources.list.d / *

## تثبيت gnupg مطلوب للتوقيع على المستودع
# pkg install -y gnupg

## تسجيل الدخول إلى مستودع gushmazuko
# curl -fsSL https://raw.githubusercontent.com/gushmazuko/metasploit_in_termux/master/gushmazuko-gpg.pubkey | gpg - عزيزي | tee $ PREFIX / etc / apt / trust.gpg.d / gushmazuko-repo.gpg

## إضافة مستودع gushmazuko لتثبيت إصدار روبي 2.7.2
# صدى 'ديب https://github.com/gushmazuko/metasploit_in_termux/raw/master gushmazuko main' | tee $ PREFIX / etc / apt / sources.list.d / gushmazuko.list

## تعيين أولوية منخفضة لجميع مستودعات gushmazuko (لأغراض أمنية)
## تعيين الأولوية القصوى لحزمة الياقوت من مستودع gushmazuko
# echo '## تعيين أولوية منخفضة لجميع مستودعات gushmazuko (لأغراض أمنية)
# طَرد: *
# دبوس: الافراج عن gushmazuko
# دبوس الأولوية: 100

## تعيين الأولوية القصوى لحزمة الياقوت من مستودع gushmazuko
# العبوة: ياقوت
# دبوس: الافراج عن gushmazuko
# Pin-Priority: 1001 '| tee $ PREFIX / etc / apt / preferences.d / preferences

# تطهير تثبيت روبي
apt تطهير روبي y
rm -fr $ PREFIX / lib / ruby ​​/ gems

ترقية pkg -y -o Dpkg :: Options :: = "- force-confnew"

# يحتاج ثنائيات
تثبيت pkg -y binutils python autoconf bison clang coreutils curl findutils apr apr-util postgresql openssl readline libffi libgmp libpcap libsqlite libgrpc libtool libxml2 libxslt ncurses جعل أدوات ncurses-utipitux ncurses ruby -o Dpkg :: Options :: = "- force-confnew"

تثبيت python3 -m pip - ترقية pip
طلبات تثبيت python3 -m pip


# في حالة حدوث أي تحذير غريب ، فربما يكون ناتجًا عن bigdecimal و pg_ext.so. حاول التعليق على هذه السطور إذا استمرت المشكلة

صدى صوت
الوسط "*** إصلاح Ruby BigDecimal"
المصدر <(curl -sL https://github.com/termux/termux-packages/files/2912002/fix-ruby-bigdecimal.sh.txt)

صدى صوت
center "*** محو مجلد metasploit القديم ..."
rm -rf $ PREFIX / opt / metasploit-framework

صدى صوت
مركز "*** جارٍ التنزيل ..."
cd $ PREFIX / opt
استنساخ بوابة https://github.com/rapid7/metasploit-framework.git --depth = 1

صدى صوت
المركز "*** التثبيت ..."
cd $ PREFIX / opt / metasploit-framework
# sed '/ rbnacl / d' -i Gemfile.lock
# sed '/ rbnacl / d' -i metasploit-framework.gemspec

#sed -i "277، \ $ s / 2.8.0 / 2.2.0 /" Gemfile.lock

مجمع تثبيت الأحجار الكريمة
أعلن NOKOGIRI_VERSION = $ (cat Gemfile.lock | grep -i nokogiri | sed 's / nokogiri [\ (\)] / (/ g' | cut -d '-f 5 | grep -oP "(.). [ [: digit:]] [\ w +]؟ [.]. ")
#sed 's | nokogiri (1. *) | nokogiri (1.8.0) | g' -i Gemfile.lock

gem install nokogiri -v $ NOKOGIRI_VERSION - --استخدام نظام المكتبات

# لـ aarch64 إذا استمرت مشكلة nokogiri افعل هذا

تكوين الحزمة build.nokogiri "- استخدام مكتبات النظام - مع-xml2-include = $ PREFIX / include / libxml2" ؛ تثبيت الحزمة

عمل حزمة تثبيت جوهرة
حزمة التحديث النشط الدعم
تحديث الحزمة - حزمة
تثبيت الحزمة -j $ (nproc --all)

# $ PREFIX / bin / find -type f-executable -exec termux-fix-shebang \ {\} \؛
# rm ./modules/auxiliary/gather/http_pdf_authors.rb
إذا [-e $ PREFIX / bin / msfconsole] ؛ إذًا
	rm $ PREFIX / bin / msfconsole
فاي
إذا [-e $ PREFIX / bin / msfvenom] ؛ إذًا
	rm $ PREFIX / bin / msfvenom
فاي
إذا [-e $ PREFIX / bin / msfrpcd] ؛ إذًا
	rm $ PREFIX / bin / msfrpcd
فاي
ln -s $ PREFIX / opt / metasploit-framework / msfconsole $ PREFIX / bin /
ln -s $ PREFIX / opt / metasploit-framework / msfvenom $ PREFIX / bin /
ln -s $ PREFIX / opt / metasploit-framework / msfrpcd $ PREFIX / bin /

منظف ​​Termux-elf $ PREFIX / lib / ruby ​​/ gems / * / gems / pg - * / lib / pg_ext.so

صدى صوت
المركز "*"
صدى -e "\ 033 [32 م إلغاء التحذيرات \ 033 [0 م"

# sed -i '355 s / :: Exception، //' $ PREFIX / bin / msfvenom
# sed -i '481، 483 {s / ^ / # /}' $ PREFIX / bin / msfvenom


# sed -Ei "s / (\ ^ \\\ c \ s +) / (\ ^ \\\ C - \\\ s) /" $ PREFIX / opt / metasploit-framework / lib / msf / core / استغلال / جهاز التحكم عن بعد / vim_soap.rb

# يحدث تحذير أثناء إنشاء الحمولة
sed -i '86 {s / ^ / # /}؛ 96 {s / ^ / # /} '$ PREFIX / lib / ruby ​​/ gems / 3.1.0 / gems / concurrent-ruby-1.0.5 / lib / concurrent / atomic/ruby_thread_local_var.rb
sed -i '442، 476 {s / ^ / # /}؛ 436، 438 {s / ^ / # /}' $ PREFIX / lib / ruby ​​/ gems / 3.1.0 / gems / logging-2.3.1 / lib /logging/diagnostic_context.rb

## تم حل مشكلة opensl

#sed -i '13، 15 {s / ^ / # /} '$ PREFIX / lib / ruby ​​/ gems / 3.1.0 / gems / hrr_rb_ssh-0.4.2 / lib / hrr_rb_ssh / transport / encryption_algorithm / functionable.rb
#sed -i '14 {s / ^ / # /} '$ PREFIX / lib / ruby ​​/ gems / 3.1.0 / gems / hrr_rb_ssh-0.4.2 / lib / hrr_rb_ssh / transport / server_host_key_algorithm / ecdsa_sha2_nistp256.rb
#sed -i '14 {s / ^ / # /} '$ PREFIX / lib / ruby ​​/ gems / 3.1.0 / gems / hrr_rb_ssh-0.4.2 / lib / hrr_rb_ssh / transport / server_host_key_algorithm / ecdsa_sha2_nistp384.rb
#sed -i '14 {s / ^ / # /} '$ PREFIX / lib / ruby ​​/ gems / 3.1.0 / gems / hrr_rb_ssh-0.4.2 / lib / hrr_rb_ssh / transport / server_host_key_algorithm / ecdsa_sha2_nistp521.rb

صدى صوت
المركز "*"
echo -e "\ 033 [اكتمل التثبيت 32 دقيقة. \ n قم بتشغيل metasploit بتنفيذ: msfconsole \ 033 [0m"
المركز "*"
