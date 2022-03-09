#########################################
# Start a ContainerLab Environment      #
# #########################################
.PHONY: deploy
deploy:
		sudo clab deploy -y clab-topos/atd-dc/atd-dc.yml --reconfigure

.PHONY: destroy
destroy:
		sudo clab destroy -t clab-topos/atd-dc/atd-dc.yml