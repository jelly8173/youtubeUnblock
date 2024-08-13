#SUBDIRS = src
dist_doc_DATA = README.md
bin_PROGRAMS = yt-unblk
yt_unblk_SOURCES = youtubeUnblock.c mangle.c args.c
#yt_unblk_CFLAGS = -DNO_FAKE_SNI
#yt_unblk_CFLAGS = -DUSE_SEG2_DELAY
yt_unblk_LDFLAGS = -lmnl -lnetfilter_queue -lnfnetlink
