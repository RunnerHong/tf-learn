## tournament api
-----------------------------------------------------------------------------------------------------------------------
[test](#filter_match)
### List open tournaments:

```json
{
    "data": [
        {
            "entry_remaining": 1,
            "tournament": {
                "start_isoformat": "2017-06-07T11:31:00+00:00", 
                "video_views": 162,　//观看量
                "tournament_url": "/battle/best-coffee-art-channelfixRu/",
                "is_sponsor_tournament": false,
                "title": "Best Coffee Art #ChannelFix",　 //
                "time_of_next_phase": null,
                "image_urls": {
                    "360": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/xRjQHhsYUtzvQ8DVaSba9V-360_0002.jpg",
                    "720": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/xRjQHhsYUtzvQ8DVaSba9V-720_0002.jpg"
                },
                "when_isoformat": "2017-06-07T09:47:09.445320+00:00",
                "votes_count": 0,　//投票总和
                "total_prize_value": 18,　//总价值
                "is_manually_open": true,
                "entries_count": 16, //已上传作品数量
                "owner": {//创办人
                    "username": "anwnjgZbQWap5arsbuAFwH",
                    "profile": {
                        "rank_label": "#106",
                        "display_name": "DanEsraelBuagas",
                        "level": 10,
                        "country": {
                            "code": "PH",
                            "name": "Philippines"　//地址
                        },
                        "group_list": [
                            "Broadcasters",
                            "SMS Verified"
                        ],
                        "followers_count": 7,
                        "avatar_url": "https://channelfix-static.s3.amazonaws.com/avatars/V7XhxXsAGSXuEENwJqhi3b.jpeg",
                        "location": "Philippines",
                        "full_name": "Dan Esrael Buagas",　//名字
                        "id": 186304,
                        "profile_url": "/profile/anwnjgZbQWap5arsbuAFwH/"　//个人资料地址
                    },
                    "is_staff": false,
                    "is_active": true,
                    "id": 186438
                },
                "video": {
                    "outputs_status": "live",　//转码完成了吗 (三种状态：Pending, Live, Error)
                    "title": "Call To Action",
                    "extension_bitrate_urls": {//播放地址
                        "mpeg4": {
                            "360": "http://channelfix-static.s3.amazonaws.com/video/enc/xRjQHhsYUtzvQ8DVaSba9V-360.mp4",
                            "720": "http://channelfix-static.s3.amazonaws.com/video/enc/xRjQHhsYUtzvQ8DVaSba9V-720.mp4"
                        },
                        "webm": {
                            "360": "http://channelfix-static.s3.amazonaws.com/video/enc/xRjQHhsYUtzvQ8DVaSba9V-360.webm",
                            "720": "http://channelfix-static.s3.amazonaws.com/video/enc/xRjQHhsYUtzvQ8DVaSba9V-720.webm"
                        }
                    },
                    "filmstrip_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/14815-merged.jpg",
                    "slug": "call-to-actionEe",
                    "thumbnail_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/xRjQHhsYUtzvQ8DVaSba9V-360_0002.jpg",　
                    "id": 14815
                },
                "id": 2306, //tournament_id, 获取tournament detail api, 获取tournament comment api
                "category_name": "Hobbies" //类别
            },
            "time_left": "1157 days, 9:46:39",
            "timeto": 0,
            "slug": "minimum-entries", //开放
            "minimumentries": 17,　//期望视频
            "started_date_isoformat": "2017-06-07T11:31:00+00:00",　//阶段开始时间　（现在的时间－阶段开始时间＝几分钟或小时前）
            "duration": "365 days, 0:00:00",
            "finished_date_isoformat": null,
            "id": 9216
        }
    ]
}
```
-----------------------------------------------------------------------------------------------------------------------
### List ranking tournaments:
```json
{
    "data": [
        {
            "tournament": {
                "start_isoformat": "2017-09-20T11:47:00+00:00",
                "video_views": 1066,　//比赛介绍视频观看量
                "tournament_url": "/battle/perfect-teeth-challenge-channelfixWk/",
                "is_sponsor_tournament": false,
                "title": "Perfect Teeth Challenge #ChannelFix",　//标题
                "time_of_next_phase": null,
                "image_urls": {
                    "360": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/8gL7q7LVxttLfR26rebU8Q-360_0008.jpg",
                    "720": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/8gL7q7LVxttLfR26rebU8Q-720_0008.jpg"
                },
                "when_isoformat": "2017-09-19T06:39:57.115012+00:00",
                "votes_count": 70,　//投票总和
                "total_prize_value": 18,　//总价值
                "is_manually_open": false,
                "entries_count": 19,　//已上传作品数量
                "owner": {　//创办人
                    "username": "u4Y2Bn5WKiz7QhGtrXroJH",
                    "profile": {
                        "rank_label": "#217",
                        "display_name": "MeasianLangcamon",
                        "level": 10,
                        "country": {
                            "code": "PH",
                            "name": "Philippines"
                        },
                        "group_list": [
                            "Broadcasters",
                            "SMS Verified"
                        ],
                        "followers_count": 16,
                        "avatar_url": "https://channelfix-static.s3.amazonaws.com/avatars/DVB8fPMDTXpbabFmmwhHuD.jpeg",
                        "location": "Philippines",
                        "full_name": "Measian Langcamon",
                        "id": 183662,
                        "profile_url": "/profile/u4Y2Bn5WKiz7QhGtrXroJH/"
                    },
                    "is_staff": false,
                    "is_active": true,
                    "id": 183665
                },
                "video": { //比赛介绍视频
                    "outputs_status": "live",
                    "title": "Call To Action",
                    "extension_bitrate_urls": {
                        "mpeg4": {
                            "360": "http://channelfix-static.s3.amazonaws.com/video/enc/8gL7q7LVxttLfR26rebU8Q-360.mp4",
                            "720": "http://channelfix-static.s3.amazonaws.com/video/enc/8gL7q7LVxttLfR26rebU8Q-720.mp4"
                        },
                        "webm": {
                            "360": "http://channelfix-static.s3.amazonaws.com/video/enc/8gL7q7LVxttLfR26rebU8Q-360.webm",
                            "720": "http://channelfix-static.s3.amazonaws.com/video/enc/8gL7q7LVxttLfR26rebU8Q-720.webm"
                        }
                    },
                    "filmstrip_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/17771-merged.jpg",
                    "slug": "call-to-actiontt",
                    "thumbnail_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/8gL7q7LVxttLfR26rebU8Q-360_0002.jpg",
                    "id": 17771
                },
                "id": 2621, //tournament_id, 获取tournament detail api, 获取tournament comment api
                "category_name": "Beauty" //类别
            },
            "time_left": "-210 days, 20:40:33.483671",　//结束倒计时
            "timeto": 0,
            "slug": "ranking",　// 判断是ranking，还是social_ranking, 然后根据//ranking_id 获取　entry video或者　social_entry video
            "started_date_isoformat": "2017-10-10T04:47:11.296971+00:00",　
            "duration": "3 days, 0:00:00",
            "finished_date_isoformat": null,
            "id": 10217　//ranking_id, 获取参赛视频列表
        }
    ]
}
```

-----------------------------------------------------------------------------------------------------------------------
### List battling tournaments:

```json
{
    "data": [
        {
            "end_date": "2017-10-15T08:03:45.857751+00:00", 
            "time_of_next_battle": "2017-10-12T08:03:45.857751+00:00",
            "tournament": {
                "start_isoformat": "2017-06-09T11:29:00+00:00",
                "video_views": 489,　//视频观看量
                "tournament_url": "/battle/low-budget-music-video-channelfixOD/",
                "is_sponsor_tournament": false,
                "title": "Low Budget Music Video #ChannelFix",　//标题
                "time_of_next_phase": "2017-10-12T08:03:45.857751+00:00",
                "image_urls": {
                    "360": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/4qLPAbQCXsjmVFqBWRehKD-360_0002.jpg",
                    "720": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/4qLPAbQCXsjmVFqBWRehKD-720_0002.jpg"
                },
                "when_isoformat": "2017-05-13T02:03:15.944328+00:00",
                "votes_count": 24,　//投票量
                "total_prize_value": 18, //总价值
                "is_manually_open": false,
                "entries_count": 16,
                "owner": {//创办人
                    "username": "c2W7UATVRwFVAoiRiuVEhD",
                    "profile": {
                        "rank_label": "#458",
                        "display_name": "MaricelSilvano",
                        "level": 10,
                        "country": {
                            "code": "PH",
                            "name": "Philippines"
                        },
                        "group_list": [
                            "Broadcasters",
                            "SMS Verified"
                        ],
                        "followers_count": 2,
                        "avatar_url": "https://channelfix-static.s3.amazonaws.com/avatars/Y7jcFuc5koyW6BNFbmUS56.jpeg",
                        "location": "Philippines",
                        "full_name": "Maricel Silvano",
                        "id": 185990,
                        "profile_url": "/profile/c2W7UATVRwFVAoiRiuVEhD/"
                    },
                    "is_staff": false,
                    "is_active": true,
                    "id": 186111
                },
                "video": {//比赛介绍视频
                    "outputs_status": "live",
                    "title": "Call To Action",
                    "extension_bitrate_urls": {
                        "mpeg4": {
                            "360": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-360.mp4",
                            "720": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-720.mp4"
                        },
                        "webm": {
                            "360": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-360.webm",
                            "720": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-720.webm"
                        }
                    },
                    "filmstrip_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/16374-merged.jpg",
                    "slug": "call-to-actionmZ",
                    "thumbnail_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/4qLPAbQCXsjmVFqBWRehKD-360_0002.jpg",
                    "id": 16374
                },
                "id": 2123,　 //tournament_id, 获取tournament detail api, 获取tournament comment api
                "category_name": "Music"　//类别
            },
            "time_left": "-208 days, 23:57:08.043523",　
            "battle_seeds": {　//16进8
                "next_seed": 8,
                "current_seed": 16
            },
            "timeto": "2017-10-12T08:03:45.857751+00:00",
            "slug": "battling",
            "started_date_isoformat": "2017-10-11T08:03:45.857751+00:00",
            "battling_time_left": "-211 days, 21:28:09.882341",　//结束倒计时
            "duration": "4 days, 0:00:00",
            "finished_date_isoformat": null,
            "id": 8562, 　//battling_id, 获取参赛视频列表
            "total_votes": 48　//总投票量
        }
    ]
}
```
-----------------------------------------------------------------------------------------------------------------------
### List winners/champions:

```json
{
    "entry": {　//参赛作品
        "final_ranked_position": 11,
        "get_place": 1,
        "has_won": true,
        "title": "MY NAME IS JAIVY GEDORIO #CHANNELFIXISAWESOME",
        "when_isoformat": "2017-08-17T10:09:00.590987+00:00",
        "video": {　//视频
            "outputs_status": "live",
            "title": "Call To Action",
            "extension_bitrate_urls": {
                "mpeg4": {
                    "360": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-360.mp4",
                    "720": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-720.mp4"
                },
                "webm": {
                    "360": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-360.webm",
                    "720": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-720.webm"
                }
            },
            "filmstrip_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/16374-merged.jpg",
            "slug": "call-to-actionmZ",
            "thumbnail_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/4qLPAbQCXsjmVFqBWRehKD-360_0002.jpg",
            "id": 16374
        },
        "image_urls": {
            "360": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/aRV4wxsH9pUs4CF2ZBqvHd-360_0002.jpg",
            "720": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/aRV4wxsH9pUs4CF2ZBqvHd-720_0002.jpg"
        },
        "id": 42983,
        "has_lost": false,
        "place": 1,
        "place_ordinal": "1st",
        "owner": {//视频作者
            "username": "tR8Hud4ehP5FXy3yhEkUc6",
            "profile": {
                "rank_label": "#5",
                "display_name": "JAIVYGEDORIO",　//昵称
                "level": 10,
                "country": {
                    "code": "PH",
                    "name": "Philippines"
                },
                "group_list": [
                    "Broadcasters",
                    "SMS Verified"
                ],
                "followers_count": 605,
                "avatar_url": "http://channelfix-static.s3.amazonaws.com/avatars/sJYJUnRGuBKk9LQZEasR2Y.jpeg",
                "full_name": "JAIVY GEDORIO",
                "profile_url": "/profile/tR8Hud4ehP5FXy3yhEkUc6/"
            },
            "is_staff": false,
            "is_active": true,
            "id": 176270
        },
        "approval": 3,
        "get_approval": "Accepted",
        "entry_url": "/battle/miss-channelfix-august-channelfix/",
        "slug": "my-name-is-jaivy-gedorio"
    },
    "tournament": "Miss ChannelFix August #ChannelFix", //标题
    "place": 1,
    "prize": {
        "product": {
            "delivery": 0,
            "delivery_days": 0,
            "description": "1st Place - $300 - Miss ChannelFix August",
            "is_shipped": false,
            "title": "1st Place - $300 - Miss ChannelFix August",
            "when_verbose": "Mon, 24 Jul 2017 22:02:35 -0000",
            "image_urls": {
                "360": "http://channelfix-static.s3.amazonaws.com/product_images/Sw5z9tX73J3nPcnzHsLp8T.jpeg",
                "720": "http://channelfix-static.s3.amazonaws.com/product_images/Sw5z9tX73J3nPcnzHsLp8T.jpeg"
            },
            "product_url": "/product/1st-place-300-miss-channelfix-august/",
            "cost_tokens": 300,　//赢得
            "sponsored": false,
            "admin_fulfilled": true,
            "owner": {
                "username": "ez3vuc2DUcCfqL3YUg7BmX",
                "profile": {
                    "rank_label": "",
                    "display_name": "InsideChannelfix(CF)",
                    "level": 10,
                    "country": {
                        "code": "PH",
                        "name": "Philippines"
                    },
                    "group_list": [
                        "Broadcasters",
                        "SMS Verified"
                    ],
                    "followers_count": 3276,
                    "avatar_url": "http://channelfix-static.s3.amazonaws.com/avatars/logo.jpeg",
                    "full_name": "Inside Channelfix (CF)",
                    "profile_url": "/InsideChannelFix/"
                },
                "is_staff": true,
                "is_active": true,
                "id": 55
            },
            "video": null,
            "id": 908
        },
        "place": 1
    }
}
```

-----------------------------------------------------------------------------------------------------------------------
### List finished tournament:
```json
{
    "data": [
        {
            "category": {
                "id": 7,
                "name": "Sports" //类别
            },
            "title": "Home Workout #ChannelFix",　//标题
            "image_urls": {
                "360": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/NEHsSSDMCgmCe8c7kooGKc-360_0005.jpg",
                "720": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/NEHsSSDMCgmCe8c7kooGKc-720_0005.jpg"
            },
            "tournament_url": "/battle/home-workout-channelfixyq/",
            "finished": "2017-10-05T04:21:54.002216+00:00",　//结束时间
            "cta_view_count": 109,
            "owner": {//创办人
                "username": "vaE68b8PAkiUXypPaVJtXQ",
                "profile": {
                    "rank_label": "#11",
                    "display_name": "FritzieLepalam",
                    "level": 10,
                    "country": {
                        "code": "PH",
                        "name": "Philippines"
                    },
                    "group_list": [
                        "Broadcasters",
                        "SMS Verified"
                    ],
                    "followers_count": 189,
                    "avatar_url": "https://channelfix-static.s3.amazonaws.com/avatars/4PMLF4TmA5ferqXyobvbxb.jpeg",
                    "location": "Cebu, Philippines",
                    "full_name": "Fritzie Lepalam",
                    "id": 164873,
                    "profile_url": "/profile/vaE68b8PAkiUXypPaVJtXQ/"
                },
                "is_staff": false,
                "is_active": true,
                "id": 164876
            },
            "video": {//视频
                "outputs_status": "live",
                "title": "Call To Action",
                "extension_bitrate_urls": {
                    "mpeg4": {
                        "360": "http://channelfix-static.s3.amazonaws.com/video/enc/NEHsSSDMCgmCe8c7kooGKc-360.mp4",
                        "720": "http://channelfix-static.s3.amazonaws.com/video/enc/NEHsSSDMCgmCe8c7kooGKc-720.mp4"
                    },
                    "webm": {
                        "360": "http://channelfix-static.s3.amazonaws.com/video/enc/NEHsSSDMCgmCe8c7kooGKc-360.webm",
                        "720": "http://channelfix-static.s3.amazonaws.com/video/enc/NEHsSSDMCgmCe8c7kooGKc-720.webm"
                    }
                },
                "filmstrip_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/17085-merged.jpg",
                "slug": "call-to-action7T",
                "thumbnail_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/NEHsSSDMCgmCe8c7kooGKc-360_0002.jpg",
                "id": 17085
            },
            "first_prize_title": "$10.00 Cash"
        }
    ]
}
```json
------------------------------------------------------------------------------------------------------------------------------------------
### Tournament Detail
```json
{
    "data": {
        "category": {
            "id": 2,
            "name": "Comedy"　//类别
        },
        "description": "Babies are funny! Upload videos of the funniest baby moments and win!",　//比赛描述
        "title": "Funny Babies #ChannelFix",　//比赛标题
        "is_manually_open": false,
        "time_of_next_phase": null,
        "image_urls": {
            "360": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/BA9NBQ2PcFxQsymKVL4dnU-360_0002.jpg",
            "720": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/BA9NBQ2PcFxQsymKVL4dnU-720_0002.jpg"　
        },
        "video_views": 36,　//比赛介绍视频观看量
        "tournament_url": "/battle/funny-babies-channelfixFO/",
        "official_prizes": [
            {
                "product": {
                    "delivery": 0,
                    "delivery_days": 0,
                    "description": "$10 Cash prize that goes to your cash wallet.", //奖品说明
                    "is_shipped": false,
                    "title": "$10.00 Cash",　//奖品名称
                    "when_verbose": "Fri, 22 Sep 2017 22:29:17 -0000",　
                    "image_urls": {
                        "360": "http://channelfix-static.s3.amazonaws.com/product_images/aki6LLY2E5knhwosUhvNgQ.jpeg",
                        "720": "http://channelfix-static.s3.amazonaws.com/product_images/aki6LLY2E5knhwosUhvNgQ.jpeg" //奖品图片
                    },
                    "product_url": "/product/10-cash/",
                    "cost_tokens": 10,　//奖品价值
                    "sponsored": true,
                    "admin_fulfilled": true,
                    "owner": {
                        "username": "ez3vuc2DUcCfqL3YUg7BmX",
                        "profile": {
                            "rank_label": "",
                            "display_name": "InsideChannelfix(CF)",
                            "level": 10,
                            "country": {
                                "code": "PH",
                                "name": "Philippines"
                            },
                            "group_list": [
                                "Broadcasters",
                                "SMS Verified"
                            ],
                            "followers_count": 3276,
                            "avatar_url": "http://channelfix-static.s3.amazonaws.com/avatars/logo.jpeg",
                            "full_name": "Inside Channelfix (CF)",
                            "id": 55,
                            "profile_url": "/InsideChannelFix/"
                        },
                        "is_staff": true,
                        "is_active": true,
                        "id": 55
                    },
                    "video": null,
                    "id": 925
                },
                "place": 1,　//奖品排名
                "id": 875
            },
           ......
        ],
        "vote_percentages": {　//投票机制
            "sponsor_score_percentage": 0,　//赞助商评分占比
            "vote_percentage": 0.49,　//观众投票
            "quality_score_percentage": 0.51　//质量得分
        },
        "video": {
            "outputs_status": "live",　//转码完成了吗 (三种状态：Pending, Live, Error)
            "title": "Call To Action",
            "extension_bitrate_urls": {　//播放地址
                "mpeg4": {
                    "360": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-360.mp4",
                    "720": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-720.mp4"
                },
                "webm": {
                    "360": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-360.webm",
                    "720": "http://channelfix-static.s3.amazonaws.com/video/enc/4qLPAbQCXsjmVFqBWRehKD-720.webm"
                }
            },
            "filmstrip_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/16374-merged.jpg",
            "slug": "call-to-actionmZ",
            "thumbnail_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/4qLPAbQCXsjmVFqBWRehKD-360_0002.jpg",　//比赛介绍视频图片
            "id": 16374
        },
        "active_phase_name": "open phase",
        "phase_timelines": [ //时间表
            {
                "duration": 7351269.512009,　//持续时间
                "started_date": "2017-07-19T04:22:00+00:00",　//开始时间
                "is_active": false,　//正在进行吗
                "name": "open phase"　//作品征集
            },
            {
                "duration": 259200,　//
                "started_date": 0, //
                "is_active": false, //
                "name": "ranking phase" //排位赛
            },
            {
	     //这个的逻辑是：总的有２的total_rounds次(即16个)方个参赛视频，
	     //第(active_round+1)轮是２**(total_rounds-active_round)到２**(total_rounds-active_round-1)(即16进)
                "total_rounds": 4,　//总的轮次
                "active_round": 0,　//当前正在进行的轮次 (0 到　total_rounds-1), 转化为人类的表示是　active_round＋１（0即第一轮）　
                "name": "battling phase",　对抗赛
                "duration": 345600,　//每一轮的时间为duration/total_rounds
                "started_date": 0, //时间不明
                "is_active": false
            }
        ],
        "owner": {
            "username": "Ei5RdiAtGzRnfhaVxrTw8B",
            "profile": {
                "rank_label": "Top10k",
                "display_name": "MitchNociras",
                "level": 10,
                "country": {
                    "code": "PH",
                    "name": "Philippines"
                },
                "group_list": [
                    "Broadcasters",
                    "SMS Verified"
                ],
                "followers_count": 1,
                "avatar_url": "http://channelfix-static.s3.amazonaws.com/avatars/XcR7WhXQNeEaP2w4oM9YE3.jpeg",
                "full_name": "Mitch Nociras",
                "id": 187965,
                "profile_url": "/profile/Ei5RdiAtGzRnfhaVxrTw8B/"
            },
            "is_staff": false,
            "is_active": true,
            "id": 188177
        },
        "official_rules": "", //规则
        "is_finished": false,
        "id": 2499,
        "tournament_entry_upload_url": "/battle/2499/entry-agreement/"
    }
}
```
------------------------------------------------------------------------------------------------------------------------------------------
<span id="filter_match">Show Match Battle<span>:

```json
{　　　//对决
    "data": {
        "left_entry_vote_count": 22, //左边参赛作品投票数
        "previous_match_pk": 0,
        "right_entry_phase_initial_position": 16,　
        "left_entry_phase_initial_position": 1,
        "right_entry": {　//右边参赛作品
            "was_auto_accepted": false,
            "title": "ChannelFix.com Let's Get Awesome (black) RAINBOW +",　//作品标题
            "quality_score_display": "1.0",　//质量得分
            "owner": {　//作者
                "username": "FMXHmyTDNTDzGoyUHsfmXf",
                "profile": {
                    "rank_label": "Newb",
                    "display_name": "EmmanuelLodovice",
                    "level": 10,
                    "country": {
                        "code": "PH",
                        "name": "Philippines"
                    },
                    "group_list": [
                        "Broadcasters",
                        "SMS Verified"
                    ],
                    "followers_count": 543,
                    "avatar_url": "https://channelfix-static.s3.amazonaws.com/avatars/XpHLF9AB727ZaorKk3x7dY.jpeg",
                    "location": "Cebu, Philippines",
                    "full_name": "Emmanuel Lodovice",
                    "id": 3,
                    "profile_url": "/name3anad/"
                },
                "is_staff": true,
                "is_active": true,
                "id": 3
            },
            "image_urls": {
                "360": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/CYbBg5zjGiaFTgPrAWe4qd-360_0002.jpg",
                "720": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/CYbBg5zjGiaFTgPrAWe4qd-720_0002.jpg"
            },
            "slug": "channelfixcom-lets-get-awesome-black-rainbow",
            "sponsor_score_label": "low",
            "quality_score_label": "low",
            "sponsor_score_display": "0.0",
            "remarks": "",
            "video": {
                "title": "ChannelFix.com Let's Get Awesome (black) RAINBOW + Bananaman + Epic Unicorn!",
                "filmstrip_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/250-merged.jpg",
                "thumbnail_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/CYbBg5zjGiaFTgPrAWe4qd-360_0002.jpg",
                "id": 250,
                "slug": "channelfixcom-lets-get-awesome-black-rainbow-bananaman-epic-unicorn"
            },
            "disqualified": false,
            "removed": false,
            "id": 261
        },
        "is_open_for_voting": false,
        "next_match_pk": 57,
        "right_entry_vote_count": 11, //右边参赛作品投票数
        "left_entry": {
            "was_auto_accepted": false,
            "title": "Gorilla - BANANAMAN!",
            "quality_score_display": "1.0",
            "owner": {
                "username": "8ToKkDtESxnMo4K5iT6UaE",
                "profile": {
                    "rank_label": "Top10k",
                    "display_name": "MichaelAngeloLarrubis",
                    "level": 4,
                    "country": {
                        "code": "PH",
                        "name": "Philippines"
                    },
                    "group_list": [],
                    "followers_count": 3,
                    "avatar_url": "https://channelfix-static.s3.amazonaws.com/avatars/MichaelAngeloPrahinogLarrub.jpeg",
                    "location": "Cebu, Philippines",
                    "full_name": "Michael Angelo Larrubis",
                    "id": 8,
                    "profile_url": "/idiotflakeslageko/"
                },
                "is_staff": false,
                "is_active": true,
                "id": 8
            },
            "image_urls": {
                "360": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/FE9AZsRnCwi85hDunKsPhU-360_0002.jpg",
                "720": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/FE9AZsRnCwi85hDunKsPhU-720_0002.jpg"
            },
            "slug": "gorilla-bananaman",
            "sponsor_score_label": "low",
            "quality_score_label": "low",
            "sponsor_score_display": "0.0",
            "remarks": "",
            "video": {
                "title": "EVOLUTION OF AWESOMENESS - Gorilla - BANANAMAN!  ChannelFix.com: You Vote, We Listen!",
                "filmstrip_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/92-merged.jpg",
                "thumbnail_url": "https://s3-ap-southeast-1.amazonaws.com/channelfix-static/video/thumbs/FE9AZsRnCwi85hDunKsPhU-360_0002.jpg",
                "id": 92,
                "slug": "evolution-of-awesomeness-gorilla-bananaman-channelfixcom-you-vote-we-listen"
            },
            "disqualified": false,
            "removed": false,
            "id": 67
        },
        "id": 56,
        "is_current_round": false　//是现在进行的轮次吗？（false 代表已经过期，或者还没开始）
    }
}

```







