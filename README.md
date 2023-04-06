# docker-compose

sudo docker-compose --help
Define and run multi-container applications with Docker.

Usage:
docker-compose [-f <arg>...] [--profile <name>...] [options] [--] [COMMAND] [ARGS...]
docker-compose -h|--help

Options:
-f, --file FILE             Specify an alternate compose file
(default: docker-compose.yml)
-p, --project-name NAME     Specify an alternate project name
(default: directory name)
--profile NAME              Specify a profile to enable
-c, --context NAME          Specify a context name
--verbose                   Show more output
--log-level LEVEL           Set log level (DEBUG, INFO, WARNING, ERROR, CRITICAL)
--ansi (never|always|auto)  Control when to print ANSI control characters
--no-ansi                   Do not print ANSI control characters (DEPRECATED)
-v, --version               Print version and exit
-H, --host HOST             Daemon socket to connect to

--tls                       Use TLS; implied by --tlsverify
--tlscacert CA_PATH         Trust certs signed only by this CA
--tlscert CLIENT_CERT_PATH  Path to TLS certificate file
--tlskey TLS_KEY_PATH       Path to TLS key file
--tlsverify                 Use TLS and verify the remote
--skip-hostname-check       Don't check the daemon's hostname against the
name specified in the client certificate
--project-directory PATH    Specify an alternate working directory
(default: the path of the Compose file)
--compatibility             If set, Compose will attempt to convert keys
in v3 files to their non-Swarm equivalent (DEPRECATED)
--env-file PATH             Specify an alternate environment file

Commands:
build              Build or rebuild services
config             Validate and view the Compose file
create             Create services
down               Stop and remove resources
events             Receive real time events from containers
exec               Execute a command in a running container
help               Get help on a command
images             List images
kill               Kill containers
logs               View output from containers
pause              Pause services
port               Print the public port for a port binding
ps                 List containers
pull               Pull service images
push               Push service images
restart            Restart services
rm                 Remove stopped containers
run                Run a one-off command
scale              Set number of containers for a service
start              Start services
stop               Stop services
top                Display the running processes
unpause            Unpause services
up                 Create and start containers





# docker_helper

A self-sufficient runtime for containers

Common Commands:
run         Create and run a new container from an image
exec        Execute a command in a running container
ps          List containers
build       Build an image from a Dockerfile
pull        Download an image from a registry
push        Upload an image to a registry
images      List images
login       Log in to a registry
logout      Log out from a registry
search      Search Docker Hub for images
version     Show the Docker version information
info        Display system-wide information

Management Commands:
builder     Manage builds
buildx*     Docker Buildx (Docker Inc., v0.10.2)
checkpoint  Manage checkpoints
compose*    Docker Compose (Docker Inc., v2.16.0)
container   Manage containers
context     Manage contexts
image       Manage images
manifest    Manage Docker image manifests and manifest lists
network     Manage networks
plugin      Manage plugins
scan*       Docker Scan (Docker Inc., v0.23.0)
system      Manage Docker
trust       Manage trust on Docker images
volume      Manage volumes

Swarm Commands:
config      Manage Swarm configs
node        Manage Swarm nodes
secret      Manage Swarm secrets
service     Manage Swarm services
stack       Manage Swarm stacks
swarm       Manage Swarm

Commands:
attach      Attach local standard input, output, and error streams to a running container
commit      Create a new image from a container's changes
cp          Copy files/folders between a container and the local filesystem
create      Create a new container
diff        Inspect changes to files or directories on a container's filesystem
events      Get real time events from the server
export      Export a container's filesystem as a tar archive
history     Show the history of an image
import      Import the contents from a tarball to create a filesystem image
inspect     Return low-level information on Docker objects
kill        Kill one or more running containers
load        Load an image from a tar archive or STDIN
logs        Fetch the logs of a container
pause       Pause all processes within one or more containers
port        List port mappings or a specific mapping for the container
rename      Rename a container
restart     Restart one or more containers
rm          Remove one or more containers
rmi         Remove one or more images
save        Save one or more images to a tar archive (streamed to STDOUT by default)
start       Start one or more stopped containers
stats       Display a live stream of container(s) resource usage statistics
stop        Stop one or more running containers
tag         Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE
top         Display the running processes of a container
unpause     Unpause all processes within one or more containers
update      Update configuration of one or more containers
wait        Block until one or more containers stop, then print their exit codes

Global Options:
--config string      Location of client config files (default "/home/victor-hugo/.docker")
-c, --context string     Name of the context to use to connect to the daemon (overrides DOCKER_HOST env var and default context set with
"docker context use")
-D, --debug              Enable debug mode
-H, --host list          Daemon socket(s) to connect to
-l, --log-level string   Set the logging level ("debug", "info", "warn", "error", "fatal") (default "info")
--tls                Use TLS; implied by --tlsverify
--tlscacert string   Trust certs signed only by this CA (default "/home/victor-hugo/.docker/ca.pem")
--tlscert string     Path to TLS certificate file (default "/home/victor-hugo/.docker/cert.pem")
--tlskey string      Path to TLS key file (default "/home/victor-hugo/.docker/key.pem")
--tlsverify          Use TLS and verify the remote
-v, --version            Print version information and quit

Run 'docker COMMAND --help' for more information on a command.



