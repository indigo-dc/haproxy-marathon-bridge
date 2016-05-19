# haproxy-marathon-bridge (DEPRECATED)
Dockerfile to build haproxy-marathon-bridge docker image 

Docs: https://mesosphere.github.io/marathon/docs/service-discovery-load-balancing.html

<pre>
docker run -d \
-e MARATHON_IPS="$node1_ip $node2_ip $node3_ip" \
--name haproxy-marathon-bridge --net host --pid host --restart always indigodatacloud/haproxy-marathon-bridge
</pre>
