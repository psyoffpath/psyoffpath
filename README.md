- š Hi, Iām @psyoffpath
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
psyoffpath/psyoffpath is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
settings.configure(
    ENV_FOR_DYNACONF="testing",
    ROOT_PATH_FOR_DYNACONF=os.path.dirname(os.path.realpath(__file__)) + "/../../../config",
    REDIS_ENABLED_FOR_DYNACONF=True,
    # Actual values are not important - fakeredis is around
    REDIS_FOR_DYNACONF={"host": "irrelevant", "port": 1111},
)
