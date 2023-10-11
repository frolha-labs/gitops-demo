kind: Role
apiVersion: rbac.authorization.k8s.io/v1
metadata:
  name: demo-pod-ro
  namespace: default
rules:
  - verbs:
      - get
      - watch
      - list
    apiGroups:
      - ''
    resources:
      - pods
