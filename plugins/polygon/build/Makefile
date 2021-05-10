# Highlight: Makefile

# adjust the 3 lines below according to your configuration
PROJECT = polygon
path_plugin = ..
COMMON_MAK = $(path_plugin)\..\common.mak

MYCFLAGS = -DRUN_LUAFAR_INIT

T_MESSAGE =

bootscript = $(path_plugin)\$(PROJECT).lua

scripts = \
  $(path_plugin)\_globalinfo.lua

modules = \
  $(path_plugin)*modules\editor.lua      \
  $(path_plugin)*modules\exporter.lua    \
  $(path_plugin)*modules\panel.lua       \
  $(path_plugin)*modules\progress.lua    \
  $(path_plugin)*modules\settings.lua    \
  $(path_plugin)*modules\sqlite.lua      \
  $(path_plugin)*modules\string_rc.lua   \
  $(path_plugin)*modules\utils.lua       \
  $(path_share)*far2\settings.lua        \
  $(path_share)*far2\simpledialog.lua

FAR_EXPORTS = \
  ANALYSE            \
  CLOSEPANEL         \
  COMPARE            \
  CONFIGURE          \
  DELETEFILES        \
  FREEFINDDATA       \
  GETFINDDATA        \
  GETOPENPANELINFO   \
  OPEN               \
  PROCESSPANELEVENT  \
  PROCESSPANELINPUT  \
  SETDIRECTORY

TEMPL       =
TEMPL_SCR   =
RCFILE      = $(PROJECT).rc
HELP        =

include $(COMMON_MAK)