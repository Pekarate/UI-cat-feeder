SET(SOURCES screens/ui_home_screen.c
    screens/ui_settings.c
    screens/ui_audioconfig.c
    screens/ui_schedule.c
    screens/ui_editslot.c
    screens/ui_info.c
    screens/ui_Screen1.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    images/ui_img_1388130735.c
    images/ui_img_1649062918.c
    images/ui_img_419196496.c
    images/ui_img_336627466.c
    images/ui_img_1236581539.c
    images/ui_img_1476654543.c
    images/ui_img_play19x19_png.c
    images/ui_img_yes20x20_png.c
    images/ui_img_no20x20_png.c)

add_library(ui ${SOURCES})
