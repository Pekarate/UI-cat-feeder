SET(SOURCES screens/ui_home_screen.c
    screens/ui_SETTINGS.c
    screens/ui_SETTINGS1.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    images/ui_img_1388130735.c
    images/ui_img_1649062918.c
    images/ui_img_419196496.c
    images/ui_img_336627466.c
    images/ui_img_1236581539.c
    images/ui_img_1476654543.c)

add_library(ui ${SOURCES})
