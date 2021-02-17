TEMPFILE := $(shell mktemp -u)

all: ldap_replication.png core_cluster.png k8s_cluster.png

%.png : %.dot
	dot -Tpng $< -o $@

clean:
	rm *.png
