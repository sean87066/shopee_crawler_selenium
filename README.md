# shopee_crawler_selenium

shopee_data = shopee("在此處放入店家url")  例如：https://shopee.tw/dajiangfreshfood

最後可以製作出json檔案

內有：
        "商店名稱" : shopee_name,
        "產品數量" : number_of_products,
        "粉絲數量" : number_of_fan,
        "評價數量" : review,
        "開始時間" : when_start,
        "賣場分類" : sale_place,
        "產品分類" : sale_cate,
        "總和排名產品" : mix_rank_products,
        "總和排名銷售數量" : mix_rank_sold,
        "總和排名內容" : mix_rank_all,
        "月排名產品" : month_rank_products,
        "月排名銷售數量" : month_rank_sold,
        "月排名內容" : month_rank_all
        
假如想要從成 excel csv  格式可以使用 shopee_dataframe
讀取json檔匯出綜合排名及月排名
