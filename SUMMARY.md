# 区块链技术指南

* [前言](README.md)
* [修订记录](revision.md)
* [如何贡献](contribute.md)
* [区块链的诞生](born/README.md)
  * [记账科技的千年演化](born/ledger_history.md)
  * [分布式记账与区块链](born/dlt_problem.md)
  * [站在前人肩膀上的比特币](born/bitcoin.md)
  * [区块链的商业价值](born/business.md)
  * [本章小结](born/summary.md)
* [核心技术概览](overview/README.md)
  * [定义与原理](overview/definition.md)
  * [技术的演化与分类](overview/dlt.md)
  * [关键问题和挑战](overview/challenge.md)
  * [趋势与展望](overview/vision.md)
  * [认识上的误区](overview/misunderstand.md)
  * [本章小结](overview/summary.md)
* [典型应用场景](scenario/README.md)
  * [应用场景概览](scenario/overview.md)
  * [金融服务](scenario/finance.md)
  * [征信和权属管理](scenario/trust.md)
  * [资源共享](scenario/sharing.md)
  * [贸易管理](scenario/trading.md)
  * [物联网](scenario/iot.md)
  * [其它场景](scenario/others.md)
  * [本章小结](scenario/summary.md)
* [分布式系统核心技术](distribute_system/README.md)
  * [一致性问题](distribute_system/intro.md)
  * [共识算法](distribute_system/consensus.md)
  * [FLP 不可能原理](distribute_system/flp.md)
  * [CAP 原理](distribute_system/cap.md)
  * [ACID 原则与多阶段提交](distribute_system/acid.md)
  * [Paxos 算法与 Raft 算法](distribute_system/paxos.md)
  * [拜占庭问题与算法](distribute_system/bft.md)
  * [可靠性指标](distribute_system/availability.md)
  * [本章小结](distribute_system/summary.md)
* [密码学与安全技术](crypto/README.md)
  * [密码学简史](crypto/history.md)
  * [Hash 算法与数字摘要](crypto/hash.md)
  * [加解密算法](crypto/algorithm.md)
  * [消息认证码与数字签名](crypto/signature.md)
  * [数字证书](crypto/cert.md)
  * [PKI 体系](crypto/pki.md)
  * [Merkle 树结构](crypto/merkle_trie.md)
  * [Bloom Filter 结构](crypto/bloom_filter.md)
  * [同态加密](crypto/homoencryption.md)
  * [其它问题](crypto/others.md)
  * [本章小结](crypto/summary.md)
* [比特币 —— 区块链思想诞生的摇篮](bitcoin/README.md)
  * [比特币项目简介](bitcoin/intro.md)
  * [实体货币到加密数字货币](bitcoin/currency.md)
  * [原理和设计](bitcoin/design.md)
  * [挖矿](bitcoin/mining.md)
  * [共识机制](bitcoin/consensus.md)
  * [闪电网络](bitcoin/lightning_network.md)
  * [侧链](bitcoin/sidechain.md)
  * [热点问题](bitcoin/other.md)
  * [相关工具](bitcoin/tools.md)
  * [本章小结](bitcoin/summary.md)
* [以太坊 —— 挣脱数字货币的枷锁](ethereum/README.md)
  * [以太坊项目简介](ethereum/intro.md)
  * [核心概念](ethereum/concept.md)
  * [主要设计](ethereum/design.md)
  * [相关工具](ethereum/tools.md)
  * [安装客户端](ethereum/install.md)
  * [使用智能合约](ethereum/smart_contract.md)
  * [智能合约案例：投票](ethereum/contract_example.md)
  * [本章小结](ethereum/summary.md)
* [超级账本 —— 面向企业的分布式账本](hyperledger/README.md)
  * [超级账本项目简介](hyperledger/intro.md)
  * [社区组织结构](hyperledger/community.md)
  * [顶级项目介绍](hyperledger/top_project.md)
  * [开发必备工具](hyperledger/tools.md)
  * [贡献代码](hyperledger/contribute.md)
  * [本章小结](hyperledger/summary.md)

* [Fabric 部署与管理](fabric/README.md)
  * [简介](fabric/intro.md)
  * [使用 Fabric 1.0 版本](fabric/1.0.md)
  * [使用 Fabric SDK Node](fabric/sdk-node.md)
  * [Fabric v0.6](fabric/v0.6/README.md)
    * [安装部署](fabric/v0.6/install.md)
    * [使用 chaincode](fabric/v0.6/usage.md)
    * [权限管理](fabric/v0.6/membersrcv-usage.md)
    * [Python 客户端](fabric/v0.6/hyperledger-py.md)
  * [小结](fabric/summary.md)
* [区块链应用开发](app_dev/README.md)
  * [简介](app_dev/intro.md)
  * [链上代码工作原理](app_dev/chaincode.md)
  * [示例一：信息公证](app_dev/chaincode_example01.md)
  * [示例二：交易资产](app_dev/chaincode_example02.md)
  * [示例三：数字货币发行与管理](app_dev/chaincode_example03.md)
  * [示例四：学历认证](app_dev/chaincode_example04.md)
  * [示例五：社区能源共享](app_dev/chaincode_example05.md)
  * [小结](app_dev/summary.md)
* [Fabric 架构与设计](fabric_design/README.md)
  * [简介](fabric_design/intro.md)
  * [架构设计](fabric_design/design.md)
  * [消息协议](fabric_design/protocol.md)
  * [小结](fabric_design/summary.md)
* [区块链服务平台设计](baas/README.md)
  * [简介](baas/intro.md)
  * [IBM Bluemix 云区块链服务](baas/bluemix.md)
  * [微软 Azure 云区块链服务](baas/azure.md)
  * [使用超级账本 Cello 搭建区块链服务](baas/cello.md)
  * [本章小结](baas/summary.md)
* [性能与评测](evaluation/README.md)
  * [简介](evaluation/intro.md)
  * [Hyperledger Fabric v0.6](evaluation/hyperledger.md)
  * [小结](evaluation/summary.md)
* [附录](appendix/README.md)
  * [术语](appendix/terms.md)
  * [常见问题](appendix/faq.md)
  * [Golang 开发相关](appendix/golang/README.md)
    * [安装与配置 Golang 环境](appendix/golang/install.md)
    * [编辑器与 IDE](appendix/golang/ide.md)
    * [高效开发工具](appendix/golang/tools.md)
  * [ProtoBuf 与 gRPC](appendix/grpc.md)
  * [参考资源链接](appendix/resources.md)
