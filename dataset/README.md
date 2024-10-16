## Dataset Information
This Question Answering dataset is a reading comprehension resource derived from Persian Wikipedia. This crowd-sourced dataset contains over 9,000 entries, each of which can either be an unanswerable question or a question with one or more answers based on the provided context. Similar to the SQuAD2.0 dataset, the inclusion of unanswerable questions allows for the development of systems that "know they don't know the answer." Additionally, the dataset includes 900 test samples. Initial models trained on this dataset, specifically using Transformers, are also accessible. All contributors to the dataset are native Persian speakers. Notably, the contexts encompass a wide range of topics from various Wikipedia categories, including History, Religion, Geography, Science, and more. Currently, each context features 7 question-and-answer pairs along with 3 unanswerable questions.

## Dataset Structure
```
{
      "title": "فارابی",
      "paragraphs": [
        {
          "qas": [
            {
              "answers": [
                {
                  "answer_start": 0,
                  "answer_end": 26,
                  "text": "ابونصر محمد بن محمد طرخانی"
                },
                {
                  "answer_start": 0,
                  "answer_end": 26,
                  "text": "ابونصر محمد بن محمد طرخانی"
                }
              ],
              "question": "اسم کامل فارابی چیه؟",
              "is_impossible": false,
              "id": 10189
            },
            {
              "answers": [
                {
                  "answer_start": 82,
                  "answer_end": 95,
                  "text": "دهکدهٔ «وسیج»"
                },
                {
                  "answer_start": 90,
                  "answer_end": 94,
                  "text": "وسیج"
                }
              ],
              "question": " فارابی در کدام روستا به دنیا امده است؟",
              "is_impossible": false,
              "id": 10191
            },
            {
              "answers": [
                {
                  "answer_start": 803,
                  "answer_end": 815,
                  "text": "به بغداد رفت"
                },
                {
                  "answer_start": 806,
                  "answer_end": 811,
                  "text": "بغداد"
                }
              ],
              "question": "فارابی در جوانی برای درس خواندن کجا رفت؟",
              "is_impossible": false,
              "id": 10193
            },
            {
              "answers": [
                {
                  "answer_start": 823,
                  "answer_end": 834,
                  "text": "متی بن یونس"
                },
                {
                  "answer_start": 823,
                  "answer_end": 834,
                  "text": "متی بن یونس"
                }
              ],
              "question": "فارابی برای تحصیل در جوانی پیش چه کسی رفت؟",
              "is_impossible": false,
              "id": 10195
            },
            {
              "answers": [
                {
                  "answer_start": 873,
                  "answer_end": 889,
                  "text": "به حرّان سفر کرد"
                },
                {
                  "answer_start": 876,
                  "answer_end": 881,
                  "text": "حرّان"
                }
              ],
              "question": "فارابی بعد از بغداد به کجا رفت؟",
              "is_impossible": false,
              "id": 10197
            },
            {
              "answers": [
                {
                  "answer_start": 939,
                  "answer_end": 963,
                  "text": "هوش سرشار و علم آموزی وی"
                },
                {
                  "answer_start": 939,
                  "answer_end": 960,
                  "text": "هوش سرشار و علم آموزی"
                }
              ],
              "question": "چه چیزی باعث شد تا فارابی خوب درس ها را یاد بگیرد؟",
              "is_impossible": false,
              "id": 10199
            },
            {
              "answers": [
                {
                  "answer_start": 1139,
                  "answer_end": 1150,
                  "text": "یحیی بن عدی"
                },
                {
                  "answer_start": 1139,
                  "answer_end": 1150,
                  "text": "یحیی بن عدی"
                }
              ],
              "question": "کدام یک از شاگرد های فارابی مسیحی بود؟",
              "is_impossible": false,
              "id": 10201
            },
            {
              "answers": [],
              "question": "مسیحی ها برای فرابی چه اوردند؟",
              "is_impossible": true,
              "id": 10203
            },
            {
              "answers": [],
              "question": "فارابی در شهر بغداد چند بار درس نخواند؟",
              "is_impossible": true,
              "id": 10204
            },
            {
              "answers": [],
              "question": "فارابی کدام شهر را برای سکونت انتخاب کرد؟",
              "is_impossible": true,
              "id": 10205
            }
          ],
          "context": "ابونصر محمد بن محمد طرخانی ملقب به فارابی، در حدود سال ۲۵۷هجری قمری/ ۸۷۰میلادی در دهکدهٔ «وسیج» از ناحیهٔ پاراب (فاراب) در فرارود (شهر اُترار کنونی در جنوب قزاقستان) یا پاریاب (فاریاب) خراسان در افغانستان کنونی به دنیا آمد. دهخدا به نقل از بدیع الزمان فروزانفر می‌نویسد: «اسم پدر او طرخان و نام جدش اوزلوغ است (اما در دانشنامه ایرانیکا رد شده است). نام ازلغ و طرخان هر دو نامهای سغدی ایرانی هستند که نام طرخان از سغدی به ترکی وارد شده است. درشرح زندگی فارابی مطلبی که بر جریان واقعی زندگی دوران طفولیت و جوانی وی باشد در کتاب‌ها وجود ندارد. ابن ابی اصیبعه دو خبر متناقض دربارهٔ او نقل می‌کند: اول اینکه فارابی در آغاز کار نگهبان باغی در دمشق بود و دوم اینکه، در عنفوان جوانی به قضاوت مشغول بود و چون به معارف دیگر آشنا شد، قضاوت را ترک کرد و با تمام میل به طرف معارف دیگر روی آورد.» در جوانی برای تحصیل به بغداد رفت و نزد «متی بن یونس» به فراگرفتن منطق و فلسفه پرداخت. سپس به حرّان سفر کرد و به شاگردی «یوحنا بن حیلان» درآمد. از آغاز کار، هوش سرشار و علم آموزی وی سبب شد که همه موضوعاتی را که تدریس می‌شد، به خوبی فرا گیرد. به زودی نام او به عنوان فیلسوف و دانشمند شهرت یافت و چون به بغداد بازگشت، گروهی از شاگردان، گرد او فراهم آمدند که «یحیی بن عدی» فیلسوف مسیحی یکی از آنان بود. "
        }
      ]
    }
```

