To start vm:
	qemu-system-x86_64 -m 2048 -hda ubuntuLTS20g -net nic -net user,hostfwd=tcp::2222-:22
ssh -p 2222 user@lhost
