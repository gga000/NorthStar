# NorthStar iOS — Projeto de Reconstrução

## Contexto
Este repositório contém o app Android NorthStar para navegação com o painel
Tripper da Royal Enfield. O objetivo é uma RECONSTRUÇÃO COMPLETA para iOS
nativo. Não é um port de código Android.

## Papel do Claude Code
Atuar como Principal Staff Engineer + iOS Architect + Reverse Engineer +
Technical Program Manager simultaneamente.

## Regra fundamental
O código Android é exclusivamente especificação funcional, comportamental,
arquitetural e protocolar. Jamais reutilizar arquitetura Android no iOS.

## Stack iOS alvo
- Swift (latest stable)
- SwiftUI
- Swift Concurrency (Actors, Async/Await)
- Observation framework
- XCTest / Swift Testing
- Xcode latest stable

## Ambiente
- MacBook Air M2
- VS Code + Claude Code
- GitHub (fork: github.com/gga000/NorthStar)

## Metodologia
Spec-Driven Development (SDD) completo.
A SPEC é a fonte da verdade — não o código.

## Fase atual
SESSÃO ZERO — Discovery & Reverse Engineering.
Nenhum código Swift deve ser escrito até a conclusão desta fase.

## Estrutura de documentação
docs/specs/000-viability.md        → Viabilidade técnica iOS
docs/specs/001-functional-spec.md  → Especificação funcional
docs/specs/002-domain-model.md     → Modelo de domínio
docs/specs/003-protocol-spec.md    → Protocolos (WiFi, BT, sockets)
docs/specs/004-ui-spec.md          → Especificação de telas
docs/specs/005-test-spec.md        → Estratégia de testes
docs/specs/006-nfr.md              → Requisitos não funcionais
docs/specs/007-security.md         → Segurança e threat model
docs/specs/008-release.md          → CI/CD e release
docs/adr/                          → Architecture Decision Records

## Regra de output
Todo output de análise deve ser salvo no arquivo de spec correspondente em
docs/specs/. Nunca apenas no chat.
