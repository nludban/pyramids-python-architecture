DIAGRAMS =				\
	cnc-app-packages		\
	cnc-processes			\
	cnc-sequence			\
	process				\
	standard-system-layers		\
	standard-component-layers	\
	system-controller-component	\
	user-interface-component	\
	executable-components		\
	dependency-example		\
	generic-pyramid

all:					\
	$(DIAGRAMS:=.png)

clean:
	/bin/rm -f $(DIAGRAMS:=.png)

PLANT = ${HOME}/bin/plantuml
#-language | more,grep...

#cnc-processes.png: cnc-processes.obj
#	tgif -print -png cnc-processes.obj

cnc-processes.png: cnc-processes.pu component-skin.pu
	$(PLANT) cnc-processes.pu

#cnc-sequence.png: cnc-sequence.obj
#	tgif -print -png cnc-sequence.obj

#PLANTUML_LIMIT_SIZE=800
cnc-sequence.png: cnc-sequence.pu component-skin.pu
	$(PLANT) cnc-sequence.pu

process.png: process.pu component-skin.pu
	$(PLANT) process.pu

#cnc-app-packages.png: cnc-app-packages.obj
#	tgif -print -png cnc-app-packages.obj

standard-system-layers.png: standard-system-layers.obj
	tgif -print -png standard-system-layers.obj

standard-component-layers.png: standard-component-layers.obj
	tgif -print -png standard-component-layers.obj

system-controller-component.png: system-controller-component.obj
	tgif -print -png system-controller-component.obj

user-interface-component.png: user-interface-component.obj
	tgif -print -png user-interface-component.obj

executable-components.png: executable-components.obj
	tgif -print -png executable-components.obj

dependency-example.png: dependency-example.obj
	tgif -print -png dependency-example.obj

cnc-app-packages.png: cnc-app-packages.obj
	tgif -print -png cnc-app-packages.obj

generic-pyramid.png: generic-pyramid.obj
	tgif -print -png generic-pyramid.obj

#--#
