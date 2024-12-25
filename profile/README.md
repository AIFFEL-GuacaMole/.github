# GUACAMole 🧬

Graph Unified Attention-based Chemical Analysis of Molecules

## 🎯 Project Goal

Cross-modal molecule representation model을 통한 ADMET/toxicity 예측 시스템 개발

### 주요 목표
- 분자 구조의 특성을 효과적으로 포착할 수 있는 robust representation 개발
- CYP 주요 isoform 억제 예측 (binary classification) SOTA 달성
- hERG blocker 예측 (binary classification) SOTA 달성

### 부가 목표
- 기타 ADMET property, toxicity property prediction task에서 SOTA 달성
- Quantum-mechanics task에서 준수한 성능 달성
- 예측 결과에 대한 설명 가능한 해석 방법 구현

## 🔍 Key Features

- 여러 모달리티(2D, 3D, 텍스트 등)를 합성하여 분자 표현을 강건하게 구성
- 기존 모델 대비 향상된 성능의 ADMET 예측
- 산업계 활용 가능한 실용적인 시스템 구현

## 🛠 Tech Stack

- Pre-training Data: PubChem, ZINC15/20, ChemBL, PCQM4Mv2
- Fine-tuning Data: TDC, MoleculeNet, Polaris
- Deep Learning Framework: PyTorch
- Key Technologies: GNN, Transformer, Multi-modal Learning

## 👥 Team Members

- 양기택
- 김종환
- 윤철희
- 홍사빈

## 📅 Project Timeline (2024.12 ~ 2025.02)

1. Model 조사 및 구현 (1-4주차)
2. Model 고도화 및 성능 개선 (4-6주차)
   - TDC leaderboard 도전
   - Polaris competition 도전
   - Aigen Dataset validation
3. 최종 발표 및 서비스 배포 (7주차)

## 🤝 In Collaboration with

[AIGEN Sciences](https://aigensciences.com/) - Harnessing AI for Real-World Drug Discovery

---
© 2024 GUACAMole Team. All Rights Reserved.
