APPS_FOLDERS=tcp-chat tcp-cli-srv udp-chat udp-cli-srv http-server-ajax-voting http-server-form-file-upload SSL

all: 
	 $(foreach AF,$(APPS_FOLDERS),(cd $(AF); make );)

clean:
	 $(foreach AF,$(APPS_FOLDERS),(cd $(AF); make clean);)

