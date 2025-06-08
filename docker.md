1 docker ps - use to check the running image
@docker ps -a`, `--all`|Show **all** containers (default shows just running)|
@docker ps -q`, `--quiet`|Only display container **IDs**|
@docker ps -l`, `--latest`|Show only the **latest created** container|
@docker ps -n <int>`|Show **last n** created containers|
@docker ps --no-trunc`|Don't **truncate** output (full container IDs, etc.)|
@docker ps -s`, `--size`|Show **container sizes**|
@docker ps --filter`, `-f`|Filter output based on **conditions**|

2 docker images -use to check all images  
|`docker images`|Shows only **top-level** images (usable/tagged)|
|`docker images -a` or `--all`|Shows **all images**, including **intermediate layers** (from builds) and **dangling images** (no tag)|
3 docker run image name - use to run image 
|`-it`|Run in **interactive mode** with a terminal (useful for shell)|
|`--name mycontainer`|Assign a **name** to the container|
|`-d`|Run in **detached** mode (in background)|
|`-p 8080:80`|**Map ports** (host:container)|
|`-v /host:/container`|**Mount volumes** (host path to container)|
|`--rm`|Automatically **remove** container after it exits|
 