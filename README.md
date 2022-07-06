# python-tricky


1. detection of langauage
   
    first install --> pip install langdetect
                      
                      
                      langdetect supports 55 languages out of the box (ISO 639-1 codes): 
                      (af, ar, bg, bn, ca, cs, cy, da, de, el, en, es, et, fa, fi, fr, gu, he,
                      hi, hr, hu, id, it, ja, kn, ko, lt, lv, mk, ml, mr, ne, nl, no, pa, pl,
                      pt, ro, ru, sk, sl, so, sq, sv, sw, ta, te, th, tl, tr, uk, ur, vi, zh-cn, zh-tw)
                      
                      
                      langdetect is a re-implementation of Google’s language-detection library from Java to Python. Simply pass your text to the imported detect function                       and it will output the two-letter ISO 693 code of the language for which the model gave the highest confidence score. (Refer to this page for a                           full list of 693 codes and their respective languages.) If you use detect_langs instead, it will output a list of the top languages that the model                       has predicted, along with their probabilities.
                      
                      
    finally ----> it convert english language to respective texts (eng is the primary language)                  
