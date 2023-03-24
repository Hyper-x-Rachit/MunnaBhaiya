import json
import os


def get_user_list(config, key):
    with open("{}/Yone/{}".format(os.getcwd(), config), "r") as json_file:
        return json.load(json_file)[key]

class Config(object):
    LOGGER = True

    API_ID = "15469484"
    API_HASH = "a4e47ac121ccd896f52fc815a9a10a8e"
    TOKEN = "5984632368:AAHUpfXfXLRCZJslAAyQkekYVo024HnrFSE"
    OWNER_ID = "5824231649"
    OWNER_USERNAME = "HYPER_X_RACHIT"
    SUPPORT_CHAT = "shichibukai_chat_group"
    JOIN_LOGGER = "-1001866753390"
    EVENT_LOGS = "-1001866753390"
    # 
    DATABASE_URL = "postgres://yone:kushal55@ls-e6c4b74049f7e42d52874d434d6c15f85c25c82a.cmcksriktjsm.ap-south-1.rds.amazonaws.com:5432/siestarobot"  # sql
    LOAD = []
    NO_LOAD = ["rss", "math"]
    WEBHOOK = False
    REDIS_URL = "redis://default:Ny2tCdk2OENQxSPIfd2yyU7igwvKzDRs@redis-14808.c283.us-east-1-4.ec2.cloud.redislabs.com:14808"

    INSPECTOR = get_user_list("elevated_users.json", "ins")
    DEV_USERS = get_user_list("elevated_users.json", "devs")
    REQUESTER = get_user_list("elevated_users.json", "req")

    CERT_PATH = None
    STRICT_GBAN = True
    PORT = "8080"
    DEL_CMDS = True
    STRICT_GBAN = True
    WORKERS = 8
    ALLOW_EXCL = True
    ALLOW_CHATS = True
    PHOTO = "https://graph.org/file/6edc69dd794eb7e0ac6d0.jpg"
    # PHOTO = "https://telegra.ph/file/f55d0598620b80aa9a1c6.jpg"
    INFOPIC = True


class Production(Config):
    LOGGER = True


class Development(Config):
    LOGGER = True
