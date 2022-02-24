${LOGIC}
controls_if
logic_compare
logic_operation
logic_negate
logic_boolean
logic_null
logic_ternary
end_category

%{LOOPS}
controls_repeat_ext
controls_whileUntil
controls_for
controls_forEach
controls_flow_statements
end_category

%{MATH}
math_number
math_arithmetic
math_single
math_trig
math_constant
math_number_property
math_round
math_on_list
math_modulo
math_constrain
math_random_int
math_random_float
var_to_int
end_category

${TEXT}
text
text_join
text_append
text_length
text_isEmpty
text_indexOf
text_charAt
text_getSubstring
text_changeCase
text_trim
text_print
text_prompt_ext
text_to_str
end_category

%{LISTS}
lists_create_with
lists_create_with
lists_repeat
lists_length
lists_isEmpty
lists_indexOf
lists_getIndex
lists_setIndex
lists_getSublist
lists_split
lists_sort
end_category

sep
%{VARIABLES}
end_category

%{FUNCTIONS}
end_category
sep

BIPES
project_metadata
localstorage_store
end_category

%{TIMING}
label_%{TIMING}
delay
utime.vars
utime.ticks_add
utime.ticks_diff
set_rtc_esp32
get_rtc_esp32
timer
utime.deadline
stop_timer
deep_sleep8266 
end_category

%{MACHINE}
CPU
ESP32 CPU
get_freq
set_freq
reset
machine_unique_id
machine_reset_cause
reset_cause_soft
reset_cause_hard
reset_cause_wdt
reset_cause_deep
end_category
inout_pins_label
pinout
gpio_set
gpio_get
adc_esp32
pwm
pwm.freq
pwm.duty
pwm.init
pwm.deinit
gpio_interrupt
end_category
end_category

%{DISPLAYS}
NeoPixel LED Strip
neopixel_init
HSL_to_RGB
neopixel_color_numbers
neopixel_color_colors
neopixel_control
neopixel_write
end_category
Character display
char_lcd_init
char_lcd_clear
char_lcd_putstr
char_lcd_moveto
char_lcd_backlight
char_lcd_display
end_category
ST7789 Display
st7789_init
st7789_bl_power
st7789_color_numbers
st7789_color_colors
st7789_pixel
st7789_line
end_category
OLED Display
init_oled
write_oled
show_oled
clear_oled
fill_oled
end_category
LED Matrix
tm1640_init
tm1640_write
tm1640_brig
tm1640_num
tm1640_custom
end_category
end_category