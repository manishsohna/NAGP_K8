**\*\*\*\***\*\***\*\*\*\*** URL \***\*\*\*\*\*\*\***\*\*\*\*\***\*\*\*\*\*\*\***\*\*\*\*\***\*\*\*\*\*\*\***\*\*\*\*\***\*\*\*\*\*\*\***

DOCKER HUB URL: https://hub.docker.com/r/dockersohna/my-repo/tags

GITHUB URL: https://github.com/manishsohna/NAGP_K8

API SERVICE URL: http://34.132.235.138/

---

**\*\*\*\***\*\*\***\*\*\*\*** Cluster Info **\*\*\*\***\*\*\*\***\*\*\*\***\***\*\*\*\***\*\*\*\***\*\*\*\***

Created cluster in GCP with below configuration

1. cluster type: standrad
2. machine type: e2-small
3. disk type: standrad (100 GB)
4. Rest of other informations kept default.

---

\***\*\*\*\*\*\*** How to Add inital data in database \***\*\*\*\*\***\*\*\*\*\***\*\*\*\*\***\*\***\*\*\*\*\***\*\*\*\*\***\*\*\*\*\***

1. Deploy required objects in the kubernetes and expose api as a load balancer service
2. In the postman, post the request (see below for more details)
   Method: Http post
   url: service end point (eg. http:// 34.132.235.138/)
   content-type: application/json
   payload should be in below format:
   {
   "cities": [{
   "name": "delhi"
   }]
   }

---

**\*\*\*\***\*\*\*\***\*\*\*\*** FILE STRUCTURE **\*\***\*\***\*\***\*\*\*\***\*\***\*\***\*\***\*\*\***\*\***\*\***\*\***\*\*\*\***\*\***\*\***\*\***

1. All kubernetes yml files are under kubernetes_obejcts folder

---
