# Hub Tài liệu ZeroClaw (Tiếng Việt)

Đây là trang chủ tiếng Việt của hệ thống tài liệu.

Đồng bộ lần cuối: **2026-02-21**.

> Lưu ý: Tên lệnh, khóa cấu hình và đường dẫn API giữ nguyên tiếng Anh. Khi có sai khác, tài liệu tiếng Anh là bản gốc. Cây tài liệu tiếng Việt đầy đủ nằm tại [vi/](vi/README.md).

Hub bản địa hóa: [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Русский](README.ru.md) · [Français](README.fr.md) · [Tiếng Việt](README.vi.md).

## Tra cứu nhanh

| Tôi muốn…                                         | Xem tài liệu                                                                  |
| -------------------------------------------------- | ------------------------------------------------------------------------------ |
| Cài đặt và chạy nhanh                              | [README.vi.md (Khởi động nhanh)](../README.vi.md) / [../README.md](../README.md) |
| Cài đặt bằng một lệnh                              | [one-click-bootstrap.md](one-click-bootstrap.md)                               |
| Tìm lệnh theo tác vụ                               | [commands-reference.md](vi/commands-reference.md)                         |
| Kiểm tra giá trị mặc định và khóa cấu hình         | [config-reference.md](vi/config-reference.md)                             |
| Kết nối provider / endpoint tùy chỉnh               | [custom-providers.md](vi/custom-providers.md)                             |
| Cấu hình Z.AI / GLM provider                        | [zai-glm-setup.md](vi/zai-glm-setup.md)                                  |
| Sử dụng tích hợp LangGraph                          | [langgraph-integration.md](vi/langgraph-integration.md)                   |
| Vận hành hàng ngày (runbook)                        | [operations-runbook.md](vi/operations-runbook.md)                         |
| Khắc phục sự cố cài đặt/chạy/kênh                   | [troubleshooting.md](vi/troubleshooting.md)                               |
| Cấu hình Matrix phòng mã hóa (E2EE)                | [matrix-e2ee-guide.md](vi/matrix-e2ee-guide.md)                           |
| Xem theo danh mục                                   | [SUMMARY.md](vi/SUMMARY.md)                                              |
| Xem bản chụp PR/Issue                               | [project-triage-snapshot-2026-02-18.md](project-triage-snapshot-2026-02-18.md) |

## Tìm nhanh (10 giây)

- Cài đặt lần đầu hoặc khởi động nhanh → [getting-started/README.md](vi/getting-started/README.md)
- Cần tra cứu lệnh CLI / khóa cấu hình → [reference/README.md](vi/reference/README.md)
- Cần vận hành / triển khai sản phẩm → [operations/README.md](vi/operations/README.md)
- Gặp lỗi hoặc hồi quy → [troubleshooting.md](vi/troubleshooting.md)
- Tìm hiểu bảo mật và lộ trình → [security/README.md](vi/security/README.md)
- Làm việc với bo mạch / thiết bị ngoại vi → [hardware/README.md](vi/hardware/README.md)
- Đóng góp / review / quy trình CI → [contributing/README.md](vi/contributing/README.md)
- Xem toàn bộ bản đồ tài liệu → [SUMMARY.md](vi/SUMMARY.md)

## Danh mục (Khuyến nghị)

- Bắt đầu: [getting-started/README.md](vi/getting-started/README.md)
- Tra cứu: [reference/README.md](vi/reference/README.md)
- Vận hành & triển khai: [operations/README.md](vi/operations/README.md)
- Bảo mật: [security/README.md](vi/security/README.md)
- Phần cứng & ngoại vi: [hardware/README.md](vi/hardware/README.md)
- Đóng góp & CI: [contributing/README.md](vi/contributing/README.md)
- Ảnh chụp dự án: [project/README.md](vi/project/README.md)

## Theo vai trò

### Người dùng / Vận hành

- [commands-reference.md](vi/commands-reference.md) — tra cứu lệnh theo tác vụ
- [providers-reference.md](vi/providers-reference.md) — ID provider, bí danh, biến môi trường xác thực
- [channels-reference.md](vi/channels-reference.md) — khả năng kênh và hướng dẫn thiết lập
- [matrix-e2ee-guide.md](vi/matrix-e2ee-guide.md) — thiết lập phòng mã hóa Matrix (E2EE)
- [config-reference.md](vi/config-reference.md) — khóa cấu hình quan trọng và giá trị mặc định an toàn
- [custom-providers.md](vi/custom-providers.md) — mẫu tích hợp provider / base URL tùy chỉnh
- [zai-glm-setup.md](vi/zai-glm-setup.md) — thiết lập Z.AI/GLM và ma trận endpoint
- [langgraph-integration.md](vi/langgraph-integration.md) — tích hợp dự phòng cho model/tool-calling
- [operations-runbook.md](vi/operations-runbook.md) — vận hành runtime hàng ngày và quy trình rollback
- [troubleshooting.md](vi/troubleshooting.md) — dấu hiệu lỗi thường gặp và cách khắc phục

### Người đóng góp / Bảo trì

- [../CONTRIBUTING.md](../CONTRIBUTING.md)
- [pr-workflow.md](vi/pr-workflow.md)
- [reviewer-playbook.md](vi/reviewer-playbook.md)
- [ci-map.md](vi/ci-map.md)
- [actions-source-policy.md](vi/actions-source-policy.md)

### Bảo mật / Độ tin cậy

> Lưu ý: Mục này gồm tài liệu đề xuất/lộ trình, có thể chứa lệnh hoặc cấu hình chưa triển khai. Để biết hành vi thực tế, xem [config-reference.md](vi/config-reference.md), [operations-runbook.md](vi/operations-runbook.md) và [troubleshooting.md](vi/troubleshooting.md) trước.

- [security/README.md](vi/security/README.md)
- [agnostic-security.md](vi/agnostic-security.md)
- [frictionless-security.md](vi/frictionless-security.md)
- [sandboxing.md](vi/sandboxing.md)
- [audit-logging.md](vi/audit-logging.md)
- [resource-limits.md](vi/resource-limits.md)
- [security-roadmap.md](vi/security-roadmap.md)

## Quản lý tài liệu

- Mục lục thống nhất (TOC): [SUMMARY.md](vi/SUMMARY.md)
- Danh mục và phân loại tài liệu: [docs-inventory.md](docs-inventory.md)

## Ngôn ngữ khác

- English: [README.md](README.md)
- 简体中文: [README.zh-CN.md](README.zh-CN.md)
- 日本語: [README.ja.md](README.ja.md)
- Русский: [README.ru.md](README.ru.md)
- Français: [README.fr.md](README.fr.md)
