zrpc/
├── client.go
├── client_test.go
├── config.go
├── config_test.go
├── internal
│   ├── auth
│   │   ├── auth.go
│   │   ├── auth_test.go
│   │   ├── credential.go
│   │   ├── credential_test.go
│   │   └── vars.go
│   ├── balancer
│   │   └── p2c
│   │       ├── p2c.go
│   │       └── p2c_test.go
│   ├── chainclientinterceptors.go
│   ├── chainclientinterceptors_test.go
│   ├── chainserverinterceptors.go
│   ├── chainserverinterceptors_test.go
│   ├── client.go
│   ├── clientinterceptors
│   │   ├── breakerinterceptor.go
│   │   ├── breakerinterceptor_test.go
│   │   ├── durationinterceptor.go
│   │   ├── durationinterceptor_test.go
│   │   ├── prometheusinterceptor.go
│   │   ├── prometheusinterceptor_test.go
│   │   ├── timeoutinterceptor.go
│   │   ├── timeoutinterceptor_test.go
│   │   ├── tracinginterceptor.go
│   │   └── tracinginterceptor_test.go
│   ├── client_test.go
│   ├── codes
│   │   ├── accept.go
│   │   └── accept_test.go
│   ├── mock
│   │   ├── deposit.pb.go
│   │   ├── deposit.proto
│   │   └── depositserver.go
│   ├── rpclogger.go
│   ├── rpclogger_test.go
│   ├── rpcpubserver.go
│   ├── rpcpubserver_test.go
│   ├── rpcserver.go
│   ├── rpcserver_test.go
│   ├── server.go
│   ├── serverinterceptors
│   │   ├── authinterceptor.go
│   │   ├── authinterceptor_test.go
│   │   ├── breakerinterceptor.go
│   │   ├── breakerinterceptor_test.go
│   │   ├── crashinterceptor.go
│   │   ├── crashinterceptor_test.go
│   │   ├── prometheusinterceptor.go
│   │   ├── prometheusinterceptor_test.go
│   │   ├── sheddinginterceptor.go
│   │   ├── sheddinginterceptor_test.go
│   │   ├── statinterceptor.go
│   │   ├── statinterceptor_test.go
│   │   ├── timeoutinterceptor.go
│   │   ├── timeoutinterceptor_test.go
│   │   ├── tracinginterceptor.go
│   │   └── tracinginterceptor_test.go
│   └── server_test.go
├── proxy.go
├── proxy_test.go
├── resolver
│   ├── internal
│   │   ├── directbuilder.go
│   │   ├── directbuilder_test.go
│   │   ├── discovbuilder.go
│   │   ├── discovbuilder_test.go
│   │   ├── etcdbuilder.go
│   │   ├── kube
│   │   │   ├── deploy
│   │   │   │   ├── clusterrolebinding.yaml
│   │   │   │   ├── clusterrole.yaml
│   │   │   │   └── serviceaccount.yaml
│   │   │   ├── eventhandler.go
│   │   │   ├── eventhandler_test.go
│   │   │   ├── targetparser.go
│   │   │   └── targetparser_test.go
│   │   ├── kubebuilder.go
│   │   ├── kubebuilder_test.go
│   │   ├── resolver.go
│   │   ├── resolver_test.go
│   │   ├── subset.go
│   │   ├── subset_test.go
│   │   └── targets
│   │       ├── endpoints.go
│   │       └── endpoints_test.go
│   ├── register.go
│   ├── register_test.go
│   ├── target.go
│   └── target_test.go
├── server.go
└── server_test.go

13 directories, 84 files
