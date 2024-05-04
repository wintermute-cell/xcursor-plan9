ALL=\
		left_ptr default \
		left_ptr_watch watch progress \
		sb_left_arrow sb_right_arrow \
		col-resize sb_h_double_arrow \
		row-resize sb_v_double_arrow \
		text ibeam xterm \
		vertical-text xterm_horiz 048008013003cff3c00c801001200000 \
		up_arrow up-arrow hand hand1 hand2 5aca4d189052212118709018842178c0 \
		question_arrow dnd-ask help \
		cross cell crosshair \
		box move dnd-move grabbing closedhand sizing 208530c400c041818281048008011002 \
		all-scroll fleur 9d800788f1b08800ae810202380a0822 size_all openhand \
		dot circle \
		fef06c8ad4c471d1adf8e88a5cde035d \
		44ffbd2878bbf06cd6db576f9f772738 \
		1c1b11cdfc2cbdb2151fa98974fcb7c8 \
		b4f035665f997d5aec485b6ff6a0a049

all: $(ALL)

install: all
	cp $(ALL) ../cursors

clean:
	rm $(ALL)

%: %.in
	xcursorgen $@.in $@

.PHONY: all install clean
