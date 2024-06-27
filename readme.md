# Web Scraping Project Portfolio

## Introduction
This portfolio showcases some of the results from my web scraping project. The data displayed here is collected from various websites and presented in JSON format.

## Project 1: Twitter Scrapping
For this project, I scraped data from twitter post about #Crypto. This data could be used for sentiment anylisis, etc

### Sample Data
```json
[
  {
    "author_name": "Jason A. Williams",
    "author_url": "",
    "post_text": "BREAKING NEWS : \n@jimcramer\n says, \u201cMr #Bitcoin is a about to go down big.\u201d\n\nWagmi.",
    "post_created_at": "2023-10-10T18:48:44.000Z",
    "image_url": [
        "https://pbs.twimg.com/amplify_video_thumb/1711815994094522368/img/_ZrTUGtf8Zit84Fg.jpg"
    ],
    "comment_count": "492",
    "retweet_count": "597",
    "like_count": "3002",
    "view_count": "602540"
  },
  {
    "author_name": "Titan of Crypto",
    "author_url": "",
    "post_text": "#Bitcoin Bounce imminent. ",
    "post_created_at": "2024-06-27T09:11:48.000Z",
    "image_url": [
        "https://pbs.twimg.com/media/GREagdIXcAEObrL?format=jpg&name=small"
    ],
    "comment_count": "113",
    "retweet_count": "180",
    "like_count": "654",
    "view_count": "23899"
  },
  {
    "author_name": "Cozomo de\u2019 Medici",
    "author_url": "",
    "post_text": "Welcome to A New Era #Bitcoin",
    "post_created_at": "2024-01-10T21:50:58.000Z",
    "image_url": [
        "https://pbs.twimg.com/ext_tw_video_thumb/1745201321467113472/pu/img/_y_I80O-r6vkeegm.jpg"
    ],
    "comment_count": "173",
    "retweet_count": "476",
    "like_count": "1947",
    "view_count": "90445"
  }
]
```

### Future Improvement
- Add Video

## Project 2: Manga site Scrapping (Mangabat)
For this project, I scraped data from Manga site. 

### Sample Data
```json
[
  {
    "story_title": "Heir Of Mythical Heroes",
    "story_url": "https://readmangabat.com/read-ym402505",
    "story_thumbnail_url": "https://avt.mkklcdnv6temp.com/24/f/30-1685950547.jpg",
    "story_authors": [
        "Ttongmas Doenjang",
        "Jagam",
        "KWON"
    ],
    "latest_chapter": [
        {
            "title": "Chapter 51",
            "chapter_url": "https://readmangabat.com/read-ym402505-chap-51"
        },
        {
            "title": "Chapter 50",
            "chapter_url": "https://readmangabat.com/read-ym402505-chap-50"
        }
    ],
    "last_updated_at": "2024-06-27",
    "viewer_count": "15.3k",
    "story_rating": "4.4"
  },
  {
    "story_title": "The Star of a Supreme Ruler",
    "story_url": "https://readmangabat.com/read-ur399084",
    "story_thumbnail_url": "https://avt.mkklcdnv6temp.com/38/e/27-1670309467.jpg",
    "story_authors": [
        "Kang Ho-poong (\uac15\ud638\ud48d)"
    ],
    "latest_chapter": [
        {
            "title": "Chapter 113",
            "chapter_url": "https://readmangabat.com/read-ur399084-chap-113"
        },
        {
            "title": "Chapter 112",
            "chapter_url": "https://readmangabat.com/read-ur399084-chap-112"
        }
    ],
    "last_updated_at": "2024-06-27",
    "viewer_count": "11.2k",
    "story_rating": "4"
  },
  {
    "story_title": "How the Pro in His Past Life Sucks the Sweet Honey",
    "story_url": "https://readmangabat.com/read-xk401277",
    "story_thumbnail_url": "https://avt.mkklcdnv6temp.com/25/u/29-1680497731.jpg",
    "story_authors": [
        "Song Sooha ",
        "Ebipo"
    ],
    "latest_chapter": [
        {
            "title": "Chapter 77",
            "chapter_url": "https://readmangabat.com/read-xk401277-chap-77"
        },
        {
            "title": "Chapter 77",
            "chapter_url": "https://readmangabat.com/read-xk401277-chap-77"
        }
    ],
    "last_updated_at": "2024-06-27",
    "viewer_count": "21.6k",
    "story_rating": "4.7"
  }
]
```

### Future Improvement
- Image from each chapter

