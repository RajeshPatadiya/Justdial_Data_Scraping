# Justdial_Data_Scraping

SCRAP NAMES AND PHONE NUMBER OF COMPANIES REGISTERED ON JUSTDIAL

GET ALL JUSTDIAL DATA IN YOUR DATABASE

URL : http://t.justdial.com/india_api_read/26june2015/searchziva.php?city=noida&state=noida&case=spcall&stype=category_list&search=Fashion Designers&docid=&lat=&long=&area=&max=30&pg_no=1&rnd1=0.08569&rnd2=0.07510&rnd3=0.20058&basedon=&nearme=&wap=2&login_mobile=

TYPE :  GET CALL

HEADERS : NO HEADERS

PARAMETERS : 

city = "you can [ass city here"

state = "you can pass state here"

case = spcall

stype = "your serach type usually category_list"

search = "SEARCH TERM"

docid = "MAKE IT BLANK"

lat = "latutude"

long = "long"

area = "AREA NAME"

max = "NO OF RESULTS"

pg_no = "PAGE NUMBER OF RESULTS"

rnd1 , rnd2 , rnd3 = "RANDOM VALUES BETWEEN 0-1 IN LARGE DECIMALS"

near_me = "YOUR NEAR LOCATION TO BE ENTERED"



SAMPLE OUTPUT : 

{
  "results": [
    {
      "docId": "011PXX11.XX11.160201180547.R1J6",
      "name": "TIARA studio and boutique",
      "distance": "",
      "contact": "+(91)-11-33633421",
      "address": "F-3,1st floor, ATS one hamlet, Sector 104, Noida - 201304",
      "NewAddress": "ATS one hamlet, Sector 104",
      "landmark": "",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.532064000000,77.383763000000",
      "paidStatus": "6",
      "compRating": "5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "0",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33633421"
      },
      "VNumber": "+(91)-11-33633421",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content1.jdmagicbox.com/noida/j6/011pxx11.xx11.160201180547.r1j6/catalogue/tiara-studio-and-boutique-sector-104-noida-e32e3.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.151008193624.S2N8",
      "name": "Vastra Gatha",
      "distance": "",
      "contact": "+(91)-11-33827644",
      "address": "Store Number 14, Hauz Khas Village-Hauz Khas, Delhi - 110016",
      "NewAddress": "Hauz Khas Village-Hauz Khas",
      "landmark": "Near Hauz Khas Social",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.542231000000,77.190002000000",
      "paidStatus": "6",
      "compRating": "4.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "0",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33827644"
      },
      "VNumber": "+(91)-11-33827644",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "462215",
            "category": "Lehenga Retailers",
            "category_display": "Lehenga Retailers",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content4.jdmagicbox.com/delhi/n8/011pxx11.xx11.151008193624.s2n8/catalogue/vastra-gatha-hauz-khas-village-hauz-khas-delhi-e3cb1.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.151010233013.G6U3",
      "name": "The Aura Boutique",
      "distance": "23.88 KM",
      "contact": "+(91)-11-33415329",
      "address": "212, Hazipur, Sector 104, Noida - 201304",
      "NewAddress": "Hazipur, Sector 104",
      "landmark": "Opposite Pathways School, Near Honey Money Top Store",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.541211000000,77.368966000000",
      "paidStatus": "6",
      "compRating": "3.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33415329"
      },
      "VNumber": "+(91)-11-33415329",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.150512153335.I8U8",
      "name": "Deepak S Chhabra Couture LLP",
      "distance": "47.38 KM",
      "contact": "+(91)-11-33452143",
      "address": "I/2057, West Patel Nagar, Delhi - 110008",
      "NewAddress": "I/2057, West Patel Nagar",
      "landmark": "",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.650667000000,77.161667000000",
      "paidStatus": "6",
      "compRating": "4",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33452143"
      },
      "VNumber": "+(91)-11-33452143",
      "totalReviews": "287",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "269832",
            "category": "Fashion Designer For Mens Wear",
            "category_display": "Fashion Designer For Mens Wear",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content4.jdmagicbox.com/delhi/u8/011pxx11.xx11.150512153335.i8u8/catalogue/deepak-s-chhabra-couture-llp-west-patel-nagar-delhi-6edg.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "287",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.140311125410.R9V3",
      "name": "Craft Boutique",
      "distance": "",
      "contact": "+(91)-11-33870488",
      "address": "23-A, Opp Kendriye Vihar, Sector 110, Noida - 201304",
      "NewAddress": "Opp Kendriye Vihar, Sector 110",
      "landmark": "Near HDFC Bank",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.532064000000,77.383763000000",
      "paidStatus": "6",
      "compRating": "4.6",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "0",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33870488"
      },
      "VNumber": "+(91)-11-33870488",
      "totalReviews": "5",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content2.jdmagicbox.com/delhi/x1/011pxx11.xx11.160331112831.j2x1/catalogue/craft-boutique-noida-sector-110-noida-226b9.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "5",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.160217103752.Q4M8",
      "name": "Vastragatha Apparels Pvt Ltd",
      "distance": "",
      "contact": "+(91)-11-33745605",
      "address": "C 65 First Floor, Sector 63, Noida - 201301",
      "NewAddress": "65 First Floor, Sector 63",
      "landmark": "",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.625989000000,77.388732000000",
      "paidStatus": "3",
      "compRating": "3.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "0",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33745605"
      },
      "VNumber": "+(91)-11-33745605",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "245165",
            "category": "Sherwanis On Hire",
            "category_display": "Sherwanis On Hire",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.160405171950.M2F3",
      "name": "Imagination By Ranu Ahuja",
      "distance": "",
      "contact": "+(91)-11-33850983",
      "address": "A 28, Sector 30, Noida - 201303",
      "NewAddress": "A 28, Sector 30",
      "landmark": "Opposite Sector 30 Club, Block A",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.573932000000,77.339112000000",
      "paidStatus": "5",
      "compRating": "5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "0",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33850983"
      },
      "VNumber": "+(91)-11-33850983",
      "totalReviews": "1",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content2.jdmagicbox.com/delhi/x8/011pxx11.xx11.160405172845.n6x8/catalogue/imagination-by-ranu-ahuja-noida-sector-30-noida-6d3db-t.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "1",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.140406203056.M5A1",
      "name": "Vogue Designer Boutique",
      "distance": "27.33 KM",
      "contact": "+(91)-11-33741330",
      "address": "Durga Market, Near Gate No. 7 of Sector 52, Sector 52, Noida - 201307",
      "NewAddress": "of Sector 52, Sector 52",
      "landmark": "",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.584562000000,77.367430000000",
      "paidStatus": "5",
      "compRating": "4.4",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33741330"
      },
      "VNumber": "+(91)-11-33741330",
      "totalReviews": "21",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content1.jdmagicbox.com/delhi/a1/011pxx11.xx11.140406203056.m5a1/catalogue/vogue-designer-boutique-sector-52-noida-4.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "21",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.141220145753.D7J3",
      "name": "Mayra Fashion Studio",
      "distance": "",
      "contact": "+(91)-11-33057498",
      "address": "I 60, Sector 41, Noida - 201303",
      "NewAddress": "I 60, Sector 41",
      "landmark": "Near Noida City Centre Metro Station",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.563981700000,77.362911700000",
      "paidStatus": "5",
      "compRating": "4.3",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "0",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33057498"
      },
      "VNumber": "+(91)-11-33057498",
      "totalReviews": "4",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content3.jdmagicbox.com/delhi/j3/011pxx11.xx11.141220145753.d7j3/catalogue/mayra-fashion-studio-sector-41-noida-0.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "4",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.151028133952.H9F9",
      "name": "Mart Queen",
      "distance": "",
      "contact": "+(91)-11-33081965",
      "address": "House Number 56, Roza Yakubpur, Greater Noida, Noida - 201310",
      "NewAddress": "Roza Yakubpur, Greater Noida",
      "landmark": "Near Janta Inter College",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.474199000000,77.503517000000",
      "paidStatus": "5",
      "compRating": "3.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "0",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33081965"
      },
      "VNumber": "+(91)-11-33081965",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "283905",
            "category": "Ladies Kurti Wholesalers",
            "category_display": "Ladies Kurti Wholesalers",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.150218132337.A9S1",
      "name": "Gargi Creation",
      "distance": "26.65 KM",
      "contact": "",
      "address": "B 10, Central Market, Sector 50, Noida - 201307",
      "NewAddress": "Central Market, Sector 50",
      "landmark": "Near Rail Nagar",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.572333000000,77.363000000000",
      "paidStatus": "5",
      "compRating": "3.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "+(91)-9910720887, +(91)-8802762382",
        "l": ""
      },
      "VNumber": "",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "484312",
            "category": "Ladies Suit Retailers",
            "category_display": "Ladies Suit Retailers",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content4.jdmagicbox.com/delhi/s1/011pxx11.xx11.150218132337.a9s1/catalogue/gargi-creation-sector-50-noida-v1rr.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011P1234005694G2M2R6",
      "name": "Aaina Boutique",
      "distance": "22.26 KM",
      "contact": "+(91)-11-33428061",
      "address": "Shop Number 36, Basement, Shahid Bhagat Singh Marg, Main Market, Sector 17, Faridabad - 121002",
      "NewAddress": "Main Market, Sector 17",
      "landmark": "Near Ekant Hotel",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.410553000000,77.328980000000",
      "paidStatus": "5",
      "compRating": "5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33428061"
      },
      "VNumber": "+(91)-11-33428061",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content1.jdmagicbox.com/delhi/r6/011p1234005694g2m2r6/catalogue/aaina-boutique-sector-17-faridabad-12vc.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.110425170938.N4N7",
      "name": "Qiyara Kids Couture",
      "distance": "",
      "contact": "+(91)-11-33428414",
      "address": "702, Sector 14, Faridabad - 121007",
      "NewAddress": "702, Sector 14",
      "landmark": "Near Manav Rachna Intl School",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.396459000000,77.331562000000",
      "paidStatus": "5",
      "compRating": "4",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "0",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33428414"
      },
      "VNumber": "+(91)-11-33428414",
      "totalReviews": "3",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content2.jdmagicbox.com/delhi/n7/011pxx11.xx11.110425170938.n4n7/catalogue/qiyara-kids-couture-sector-14-faridabad-t5ti-t.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "3",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.151029131532.B5D6",
      "name": "Pastiche The Fabric Salon",
      "distance": "",
      "contact": "+(91)-11-33428941",
      "address": "C-66, NIT, Faridabad - 121001",
      "NewAddress": "C-66, NIT",
      "landmark": "Opposite ESI Hospital",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.380064000000,77.304444000000",
      "paidStatus": "5",
      "compRating": "4.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "0",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33428941"
      },
      "VNumber": "+(91)-11-33428941",
      "totalReviews": "1",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "1",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.131104191503.V5E2",
      "name": "Saleeka The Boutique",
      "distance": "",
      "contact": "+(91)-11-33429021",
      "address": "Shop Number 14 & 15, Phool Singh Complex, Sector 104, Noida - 201301",
      "NewAddress": "Sector 104, ",
      "landmark": "Near Pathways School",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.584672000000,77.330689000000",
      "paidStatus": "5",
      "compRating": "3.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "0",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33429021"
      },
      "VNumber": "+(91)-11-33429021",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content1.jdmagicbox.com/delhi/e2/011pxx11.xx11.131104191503.v5e2/catalogue/saleeka-the-boutique-noida-ho-noida-0.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.150519144553.I2A1",
      "name": "Deepika Chadha Designs",
      "distance": "30.11 KM",
      "contact": "+(91)-11-33491737",
      "address": "A 67, Sector 4, Noida - 201301",
      "NewAddress": "A 67, Sector 4",
      "landmark": "Near HDFC Bank",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.582698805556,77.325515722222",
      "paidStatus": "5",
      "compRating": "4",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33491737"
      },
      "VNumber": "+(91)-11-33491737",
      "totalReviews": "1",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content4.jdmagicbox.com/noida/a1/011pxx11.xx11.150519144553.i2a1/catalogue/deepika-chadha-designs-sector-4-noida-fd3ea.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "1",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.120318170539.S9H6",
      "name": "Razaa",
      "distance": "30.33 KM",
      "contact": "+(91)-11-33988188",
      "address": "Office Number A 45, First Floor, Sector 4, Noida - 201301",
      "NewAddress": "First Floor, Sector 4",
      "landmark": "Near HDFC Bank",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.582372000000,77.322237000000",
      "paidStatus": "5",
      "compRating": "4.1",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33988188"
      },
      "VNumber": "+(91)-11-33988188",
      "totalReviews": "18",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content3.jdmagicbox.com/delhi/h6/011pxx11.xx11.120318170539.s9h6/catalogue/razaa-sector-4-noida-3.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "18",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.151123144259.K7K4",
      "name": "Angrakha Boutique",
      "distance": "31.37 KM",
      "contact": "+(91)-11-33825362",
      "address": "RTG 22, Royal Tower, Indirapuram, Ghaziabad - 201014",
      "NewAddress": "Royal Tower, Indirapuram",
      "landmark": "",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.637658000000,77.377633000000",
      "paidStatus": "2",
      "compRating": "3.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33825362"
      },
      "VNumber": "+(91)-11-33825362",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content4.jdmagicbox.com/delhi/k4/011pxx11.xx11.151123144259.k7k4/catalogue/angrakha-boutique-indirapuram-ghaziabad-2d136.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.130223121603.C4L9",
      "name": "Shagun",
      "distance": "31.8 KM",
      "contact": "+(91)-11-33427018",
      "address": "230, Sihani Gate, Ghaziabad - 201001",
      "NewAddress": "Sihani Gate, ",
      "landmark": "Near Navyug Market",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.665822000000,77.427095000000",
      "paidStatus": "5",
      "compRating": "4.7",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33427018"
      },
      "VNumber": "+(91)-11-33427018",
      "totalReviews": "7",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "12745",
            "category": "Saree Retailers",
            "category_display": "Saree Retailers",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content1.jdmagicbox.com/delhi/l9/011pxx11.xx11.130223121603.c4l9/catalogue/shagun-ghaziabad-oc6o.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "7",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.130220211501.C5S7",
      "name": "The Aura Boutique",
      "distance": "32.39 KM",
      "contact": "+(91)-11-33415331",
      "address": "Af-10 1st Floor, Aditya City Centre, Indirapuram, Ghaziabad - 201014",
      "NewAddress": "Aditya City Centre, Indirapuram",
      "landmark": "",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.638352000000,77.360444000000",
      "paidStatus": "2",
      "compRating": "3.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33415331"
      },
      "VNumber": "+(91)-11-33415331",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content4.jdmagicbox.com/ghaziabad/s7/011pxx11.xx11.130220211501.c5s7/catalogue/the-aura-boutique-indirapuram-ghaziabad-369b1.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.111117102036.H4T4",
      "name": "The Citrine Design Studio",
      "distance": "32.32 KM",
      "contact": "+(91)-11-33984308",
      "address": "L 26, Kalkaji, Delhi - 110019",
      "NewAddress": "L 26, Kalkaji",
      "landmark": "Behind Deshbandhu Apartment",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.527013000000,77.257225000000",
      "paidStatus": "5",
      "compRating": "4",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33984308"
      },
      "VNumber": "+(91)-11-33984308",
      "totalReviews": "5",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "1",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content3.jdmagicbox.com/delhi/t4/011pxx11.xx11.111117102036.h4t4/catalogue/the-citrine-design-studio-kalkaji-Delhi-63a75.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "5",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.140507184033.D6J6",
      "name": "Maithili Fashion Boutique",
      "distance": "32.48 KM",
      "contact": "+(91)-11-33743113",
      "address": "Ground Floor, 14, Rajhans Plaza, Indirapuram, Ghaziabad - 201014",
      "NewAddress": "Rajhans Plaza, Indirapuram",
      "landmark": "Opposite Aditya Mall",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.639503100000,77.360674700000",
      "paidStatus": "5",
      "compRating": "4",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33743113"
      },
      "VNumber": "+(91)-11-33743113",
      "totalReviews": "1",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "458236",
            "category": "Ladies Salwar Kameez Designers",
            "category_display": "Ladies Salwar Kameez Designers",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "1",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content1.jdmagicbox.com/delhi/j6/011pxx11.xx11.140507184033.d6j6/catalogue/maithili-fashion-boutique-indirapuram-ghaziabad-2.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "1",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.100302162125.A3E1",
      "name": "Saheli",
      "distance": "32.45 KM",
      "contact": "+(91)-11-39549979",
      "address": "Lower Ground Floor 109, Orange County Market, Indirapuram, Ghaziabad - 201014",
      "NewAddress": "Orange County Market, Indirapuram",
      "landmark": "Opposite Aditya Mall",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.641200000000,77.363983000000",
      "paidStatus": "5",
      "compRating": "4.4",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-39549979"
      },
      "VNumber": "+(91)-11-39549979",
      "totalReviews": "18",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content3.jdmagicbox.com/delhi/e1/011pxx11.xx11.100302162125.a3e1/catalogue/saheli-indirapuram-ghaziabad-3.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "18",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.130611190719.K3I8",
      "name": "Kalka Boutique",
      "distance": "32.45 KM",
      "contact": "+(91)-11-33828644",
      "address": "B 112 B Basement, Deshbandhu College Road, Kalkaji, Delhi - 110019",
      "NewAddress": "Deshbandhu College Road, Kalkaji",
      "landmark": "Opposite South Park",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.536313000000,77.260925000000",
      "paidStatus": "5",
      "compRating": "3.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33828644"
      },
      "VNumber": "+(91)-11-33828644",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.150115122337.K5U9",
      "name": "Newyork Sherry",
      "distance": "33.5 KM",
      "contact": "+(91)-11-33059138",
      "address": "I 1676, Chittaranjan Park, Delhi - 110019",
      "NewAddress": "I 1676, Chittaranjan Park",
      "landmark": "Near Market Number 1",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.537547000000,77.249687000000",
      "paidStatus": "2",
      "compRating": "4.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33059138"
      },
      "VNumber": "+(91)-11-33059138",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "458898",
            "category": "Bridal Lehenga Retailers",
            "category_display": "Bridal Lehenga Retailers",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.130718184630.Y9G7",
      "name": "Fashion Bandwagon",
      "distance": "33.6 KM",
      "contact": "+(91)-11-33416444",
      "address": "C 1, First Floor, RK Tower, Vaishali Sector 4, Ghaziabad - 201010",
      "NewAddress": "RK Tower, Vaishali Sector 4",
      "landmark": "Near Shopprix Mall",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.640462000000,77.343292000000",
      "paidStatus": "3",
      "compRating": "4.8",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33416444"
      },
      "VNumber": "+(91)-11-33416444",
      "totalReviews": "6",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content3.jdmagicbox.com/ghaziabad/g7/011pxx11.xx11.130718184630.y9g7/catalogue/fashion-bandwagon-vaishali-sector-4-ghaziabad-d2me.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "6",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.121211163924.V9L4",
      "name": "Designer Var Shi",
      "distance": "33.25 KM",
      "contact": "+(91)-11-33636680",
      "address": "Shop Number 1, 1st Floor, Krishna Market, Kalkaji, Delhi - 110019",
      "NewAddress": "Krishna Market, Kalkaji",
      "landmark": "Opposite Deshbandhu College & Near Aggarwal Sweets",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.541662000000,77.254905000000",
      "paidStatus": "5",
      "compRating": "4.6",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33636680"
      },
      "VNumber": "+(91)-11-33636680",
      "totalReviews": "5",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "1",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content1.jdmagicbox.com/delhi/l4/011pxx11.xx11.121211163924.v9l4/catalogue/designer-var-shi-kalkaji-Delhi-0.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "5",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.151027170718.E2M2",
      "name": "Vriti Boutique & Collection",
      "distance": "33.5 KM",
      "contact": "+(91)-11-33428280",
      "address": "Plot No 117, Main Road And Jagat Market, Vasundhara Sector 5, Ghaziabad - 201012",
      "NewAddress": "And Jagat, Vasundhara Sector 5",
      "landmark": "Near Olive County",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.661488000000,77.379678000000",
      "paidStatus": "2",
      "compRating": "3.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33428280"
      },
      "VNumber": "+(91)-11-33428280",
      "totalReviews": "2",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content3.jdmagicbox.com/delhi/m2/011pxx11.xx11.151027170718.e2m2/catalogue/vriti-boutique-collection-vasundhara-sector-5-ghaziabad-tgq3.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "2",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.140804115235.H1Y7",
      "name": "Sundri",
      "distance": "35.89 KM",
      "contact": "+(91)-11-33434585",
      "address": "18 And 23, Archana Shopping Complex, Greater Kailash 1, Delhi - 110048",
      "NewAddress": "Shopping, Greater Kailash 1",
      "landmark": "Near NDTV Office",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.553763888889,77.231605555556",
      "paidStatus": "5",
      "compRating": "4.5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33434585"
      },
      "VNumber": "+(91)-11-33434585",
      "totalReviews": "8",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "4298",
            "category": "Boutiques",
            "category_display": "Boutiques",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content1.jdmagicbox.com/delhi/y7/011pxx11.xx11.140804115235.h1y7/catalogue/sundri-greater-kailash-1-delhi-0.jpg?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "8",
      "minimum_order": "",
      "favflag": 0
    },
    {
      "docId": "011PXX11.XX11.150609125850.E7N1",
      "name": "Svelte Design",
      "distance": "35.87 KM",
      "contact": "+(91)-11-33490512",
      "address": "M 113, Basement, Greater Kailash 1, Delhi - 110048",
      "NewAddress": "Basement, Greater Kailash 1",
      "landmark": "Behind M Block Market",
      "startPoint": "28.403632000000,77.556210000000",
      "companyGeocodes": "28.528164800000,77.218185100000",
      "paidStatus": "5",
      "compRating": "5",
      "resultType": "general",
      "verified": "1",
      "rateThis": "1",
      "price_range": 0,
      "closeddown_flag": 0,
      "mappointer": "1",
      "an": {
        "t": "",
        "m": "",
        "l": "+(91)-11-33490512"
      },
      "VNumber": "+(91)-11-33490512",
      "totalReviews": "1",
      "AlsoListedIn": {
        "arr_len": "5",
        "also_content": [
          {
            "cat_id": "",
            "category": "Fashion Designers",
            "category_display": "Fashion Designers",
            "movietime": "",
            "price": 0
          },
          {
            "cat_id": "276574",
            "category": "Readymade Garment Retailers",
            "category_display": "Readymade Garment Retailers",
            "movietime": "",
            "price": 0
          }
        ]
      },
      "guarantee": "",
      "show": "",
      "video": "0",
      "fratings": {
        "total": "0",
        "ratings": []
      },
      "city": "Delhi",
      "myratings": [],
      "pqt": "",
      "pqtr": "",
      "shopfront": 0,
      "thumbnail": "http://content3.jdmagicbox.com/delhi/n1/011pxx11.xx11.150609125850.e7n1/catalogue/svelte-design-greater-kailash-1-delhi-1-t.png?output-quality=60",
      "vertical_data": [],
      "vertical_type_flag": [],
      "islogo": 0,
      "totJdReviews": "1",
      "minimum_order": "",
      "favflag": 0
    }
  ],
  "nearmeDetails": "",
  "catid": "442233",
  "trending_flag": 0,
  "trending_nid": "",
  "keyword": "Fashion Designers",
  "keywordResults": [],
  "moreKeywords": "0",
  "totalNumberofResults": "500",
  "sortingOption": {
    "basedon": "distance,rating",
    "sort": "",
    "char": ""
  },
  "ratingsTab": "1",
  "pncdbd": "201304",
  "ismovie": "0",
  "sort_price_tag": 0,
  "sort_price": [],
  "view_flag": "0",
  "filter_flag": "0",
  "image_path": "http://akam.cdn.jdmagicbox.com/images/jdcategories/10200775.jpg?output-quality=60",
  "view": "1",
  "national_catid": "10200775",
  "number_mask": 0,
  "bestDeal": "|~|Fill this form and get best deals from|~|Fashion Designers",
  "bd_text": "Best Deal",
  "resultString": "near Noida",
  "aka": "",
  "other": 0
}
