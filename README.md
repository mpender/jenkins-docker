docker run -d --privileged=true -v /sys/fs/cgroup:/sys/fs/cgroup:ro  -p 8080:8080 -v $some_dir:/var/lib/jenkins mpender/jenkins-docker


exposes jenkins GUI
