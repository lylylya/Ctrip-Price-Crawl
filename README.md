# Ctrip-Price-Crawl
1. It is a project to crawl hotel lists and a hotel detailed information.
2. **Code Purpose**: The code is just for data collecting skills learning! Not for Any Commercial Use!

## 1. Project Discription
It is a project to crawl Beijing 5 star hotel via https://www.ctrip.com

## 2. Code Discription
1. Beijing_5_Star_Hotel_Lists.py
- Scrap the Beijing 5 star hotel lists and save in a csv file in Data dierectory.
- Crawl the detailed information of a specific hotel according to its index in the csv file above.
2. HotelDetailInfo_Example.py
- It is an example to scrap a specific hotel. 
3. Scrap_by_date.py
- It aims to scrap the specific hotel by date you input.
4. Scrap_Comments.py
- It aims to scrape a specific hotel comments. In this code, I scrape Beijing Kerry Hotel.
- Using (Selenium)[https://www.seleniumhq.org]

## 3. Results
1. Beijing 5 Star Hotel Lists
![Image](https://github.com/icmpnorequest/Ctrip-Price-Crawl/blob/master/Image/1.%20Hotel%20Lists%20csv.png)

2. Search the detailed hotel information
- Hotel(index=0)
![Image](https://github.com/icmpnorequest/Ctrip-Price-Crawl/blob/master/Image/2.%20Hotel%200%20Result.png)

- Hotel(index=170)
![Image](https://github.com/icmpnorequest/Ctrip-Price-Crawl/blob/master/Image/3.%20Hotel%20170%20Result.png)

3. Scrap by date
![Image](https://github.com/icmpnorequest/Ctrip-Price-Crawl/blob/master/Image/4.%20Scrap%20by%20date.png)

4. Scrap Comments
![Image](https://github.com/icmpnorequest/Ctrip-Price-Crawl/blob/master/Image/5.%20Scrap%20Kerry%20Comments.png)

## 4. Detailed Blog
I have completed the detailed project discription in my blog (https://blog.csdn.net/pandalaiscu/article/details/87720709) in Chinese.
Web Scrapers are **time-sensitive!** As I know, Ctrip has already detected Selenium and not allow to see the comments via Selenium. But, you can see the comments by open the Firefox browser manually. They have already achieved Bot Detection, Browser Fingerprinting and etc. techniques.
If you like my project, please star it for my hard work. If you have any questions, please feel free to contact/issue me.
Thanks in advance!

## 5. License
MIT License

Copyright (c) 2019 icmpnorequest

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
