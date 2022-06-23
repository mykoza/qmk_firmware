
    [_BUTTON] = LAYOUT(
        // KC_ESC, KC_1,    KC_2,    KC_3,    KC_4,    KC_5,                      KC_6,    KC_7,    KC_8,    KC_9,    KC_0,    KC_MINUS, /
        // KC_NO,  U_UND,   U_CUT,   U_CPY,   U_PST,   U_RDO,                     U_RDO,   U_PST,   U_CPY,   U_CUT,   U_UND,   KC_NO, /
        // KC_NO,  KC_LGUI, KC_LALT, KC_LCTL, KC_LSFT, KC_TRNS,                   KC_TRNS, KC_LSFT, KC_LCTL, KC_LALT, KC_LGUI, KC_NO, /
        // KC_NO,  U_UND,   U_CUT,   U_CPY,   U_PST,   U_RDO,   KC_NO,     KC_NO, U_RDO,   U_PST,   U_CPY,   U_CUT,   U_UND,   KC_NO, /
        //                  KC_NO,   KC_BTN2, KC_BTN3, KC_BTN1, KC_TAB,    KC_NO, KC_BTN1, KC_BTN3, KC_BTN2, KC_NO
        KC_ESC, KC_1,    KC_2,    KC_3,    KC_4,    KC_5,                      KC_6,    KC_7,    KC_8,    KC_9,    KC_0,    KC_MINUS,
        KC_NO,  U_UND,   U_CUT,   U_CPY,   U_PST,   U_RDO,                     U_RDO,   U_PST,   U_CPY,   U_CUT,   U_UND,   KC_NO,
        KC_NO,  KC_LGUI, KC_LALT, KC_LCTL, KC_LSFT, KC_TRNS,                   KC_TRNS, KC_LSFT, KC_LCTL, KC_LALT, KC_LGUI, KC_NO,
        KC_NO,  U_UND,   U_CUT,   U_CPY,   U_PST,   U_RDO,   KC_NO,     KC_NO, U_RDO,   U_PST,   U_CPY,   U_CUT,   U_UND,   KC_NO,
                         KC_NO,   KC_BTN2, KC_BTN3, KC_BTN1, KC_TAB,    KC_NO, KC_BTN1, KC_BTN3, KC_BTN2, KC_NO
    )

        case _BUTTON:
            oled_write_P(PSTR("Butt\n"), false);
            break;
