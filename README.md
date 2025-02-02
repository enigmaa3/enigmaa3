-

<!---import requests

def make_call(Almunharif):
    url = 'https://callmyphone.org/do-call'
    
    
    headers = {
        'authority': 'callmyphone.org',
        'accept': 'application/json, text/javascript, */*; q=0.01',
        'accept-language': 'ar-EG,ar;q=0.9,en-US;q=0.8,en;q=0.7',
        'content-type': 'application/x-www-form-urlencoded; charset=UTF-8',
        'cookie': 'remember-number-checked=1; uid=6fd833af-1328-4806-8c10-0e93dd567967; _ga=GA1.2.73591098.1727769191; _gid=GA1.2.87021946.1727769191; _ym_uid=1727769192698930664; _ym_d=1727769192; _ym_isad=2; _ym_visorc=w; _ga_06F7KQF3Y7=GS1.2.1727775347.2.0.1727775347.60.0.0; _ga_9C48LP7X6Q=GS1.2.1727775347.2.0.1727775347.0.0.0',
        'origin': 'https://callmyphone.org',
        'referer': 'https://callmyphone.org/app',
        'sec-ch-ua': '"Not-A.Brand";v="99", "Chromium";v="124"',
        'sec-ch-ua-mobile': '?1',
        'sec-ch-ua-platform': '"Android"',
        'sec-fetch-dest': 'empty',
        'sec-fetch-mode': 'cors',
        'sec-fetch-site': 'same-origin',
        'user-agent': 'Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Mobile Safari/537.36',
        'x-requested-with': 'XMLHttpRequest'
    }
    
   
    data = {
        'phone': Almunharif,
        'browser': 'undefined;',
        'fgp': 'cf36fcd3f2361ce03bd736bfcddf428a', 
        'fgp2': 'e2c3239a188e64fdfd1cc085930ff92a',  
        'rememberNumber': '1'
    }
    
   
    response = requests.post(url, headers=headers, data=data)
    
   
    print("تم إرسال المكالمة بنجاح.")


Almunharif = input("أدخل رقم الهاتف : ")
make_call(Almunharif)
