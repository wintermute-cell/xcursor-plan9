SRC = $(wildcard *.in)
GEN = $(SRC:%.in=%)
LINKS= \
	left_ptr right_ptr top_left_arrow xterm \
	X_cursor plus \
	crosshair \
	top_side based_arrow_top \
	top_left_corner ul_angle \
	top_right_corner ur_angle \
	bottom_side based_arrow_down \
	bottom_left_corner ll_angle \
	bottom_right_corner lr_angle \
	right_side right_tee \
	left_side left_tee

all: $(GEN) $(LINKS)

clean:
	rm $(GEN) $(LINKS)

%: %.in %.png
	xcursorgen $@.in $@


left_ptr right_ptr top_left_arrow xterm: arrow
	cp $< $@

X_cursor plus: cross
	cp $< $@

crosshair: sight
	cp  $< $@

top_side based_arrow_top: t
	cp $< $@

top_left_corner ul_angle: tl
	cp $< $@

top_right_corner ur_angle: tr
	cp $< $@

bottom_side based_arrow_down: b
	cp $< $@

bottom_left_corner ll_angle: bl
	cp $< $@

bottom_right_corner lr_angle: br
	cp $< $@

right_side right_tee: r
	cp $< $@

left_side left_tee: l
	cp $< $@

.PHONY: all clean
