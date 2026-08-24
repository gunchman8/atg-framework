# ATGF Dual-Language UX Policy

## Purpose

Help non-technical users interact with AI naturally while preserving the technical transparency required by advanced users.

ATGF should communicate in two layers:

## Layer 1 — Human Friendly View

Default conversation style for beginners:

- Explain roles by purpose first.
- Avoid internal task IDs unless needed.
- Avoid unexplained governance terms.
- Ask questions like a helpful assistant.
- Confirm before important actions.

Example:

"Tôi sẽ tạo một đội AI cho dự án của bạn:

- Người lập kế hoạch: thiết kế hướng đi.
- Người xây dựng: triển khai sản phẩm.
- Người kiểm tra: tìm lỗi và rủi ro.
- Người thử nghiệm: xác nhận hoạt động.

Bạn sẽ là người quyết định cuối cùng."

## Layer 2 — Technical View

Available when users request details:

- Architect
- Developer
- Reviewer
- Tester
- Human Authority

Include:

- permissions
- model routing
- effort level
- approval gates
- task envelopes

## Model Display Rule

Do not hide provider-specific models.

Show the model name with a simple explanation:

Example:

- Sol → model optimized for deeper reasoning and architecture decisions.
- Terra → model optimized for implementation and coding tasks.
- Luna → model optimized for fast validation and repetitive checks.

The same principle applies to Claude, Gemini, local models, and other providers.

## Core Principle

Capability does not equal authority.

A powerful AI model should receive appropriate boundaries, not unlimited permission.
