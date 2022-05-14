# Ternary Conditional Operator


## معامل الشرط الثلاثي Ternary Conditional Operator

عند استخدام معامل الشرط الثلاثي سيتم اختبار شرط ما، وفي حال تحقق الشرط فإنه يعود بالقيمة الأولى، وفي حال لم يتحقق فإنه يعود بالقيمة الثانية كما هو موضح بالشكل التالي:


    result =  condition ? firstExpression : secondExpression


- تمثل `condition`  التعبير الشرطي
- تمثل  `firstExpression` الأمر البرمجي الذي سيتم تنفيذه عندما تكون نتيجة الشرط صحيحة ويكون بعد `?`
- تمثل `secondExpression` الأمر البرمجي الذي سيتم تنفيذه عندما تكون نتيجة الشرط خاطئة ويكون بعد `:` 

لتوضيح الفكرة، لاحظ معي المثال التالي: 


    void main() {
    var fahadAge = 22;
    var salehAge = 30;
    var result = khalidAge > salehAge ? "Fahad is older than Saleh" : "Fahad is not older than Saleh";
    print(result);
    }


- **المخرجات****ات:**


    Khalid is not older than Saleh

في المثال السابق قمنا باستخدام معامل الشرط الثلاثي، والذي بدوره سيقوم باختبار ما إذا المتغير fahadAge أكبر من المتغير `salehAge`، وبناءًا على ذلك قام بإسناد القيمة المناسبة إلى المتغير `result`. لاحظ انه تم اسناد القيمة `Khalid is not older than Saleh` للمتغير `result`، وذلك لعدم تحقق الشرط `khalidAge` `>` `salehAge`.

