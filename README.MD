# ***************     DockerProxy     ***************

# lantern
	service port: 5168

# shadowsocks
	service port: 5198
	password: docker
	method: aes-256-cfb

# sshd
	service port: 22
	user: root
	password: docker
