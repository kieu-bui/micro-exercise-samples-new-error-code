# Micro-exercise samples – theo dạng bài tập

Tổng hợp từ repo `micro-excercise-samples-6-26`. 7 file JSON tương ứng 7 dạng bài tập (1–7) trong Notion *Bài tập AI Micro-exercise*.
Mỗi file gồm 3 khối JSON nối tiếp, mỗi khối là 1 bài tập chọn ngẫu nhiên (ưu tiên error_code khác nhau), gồm `input` (input mẫu của file gốc) và `output`.

| File | # | error_code (mới) | Mã mới | error_code cũ | id | Nguồn |
|---|---|---|---|---|---|---|
| `1. Multiple Choice - Single.json` | 1 | `weak_information_flow` | CC08 | `unclear_information_relationship` | `cc_uir_01` | `Nhóm lỗi 2 (CC)/2.2. Không có mối quan hệ giữa 2 thông tin.json` |
| `1. Multiple Choice - Single.json` | 2 | `weak_information_flow` | CC08 | `misplaced_emphasis` | `coh_emphasis_env_9q1m4` | `Nhóm lỗi 2 (CC)/2.4. Sai trọng tâm nhấn mạnh dẫn đến liên kết lỏng lẻo.json` |
| `1. Multiple Choice - Single.json` | 3 | `weak_development_and_support` | TR05 | `underdeveloped_reasoning` | `sample_02` | `Nhóm lỗi 1-2 (TR)/1-2.7. Lập luận thiếu thuyết phục (Không giải thích rõ mối quan hệ nhân quả hoặc nêu các vấn đề trừu tượng mà không có ví dụ).json` |
| `2. Multiple Choice - Multiple.json` | 1 | `faulty_key_feature_selection` | TA02 | `missing_data_support` | `data_support_env_02` | `Nhóm lỗi 1-1 (TA)/1-1.3. Đề cập thiếu dữ liệu của các chi tiết.json` |
| `2. Multiple Choice - Multiple.json` | 2 | `unclear_or_missing_position` | TR03 | `unclear_stance` | `tr_us_02` | `Nhóm lỗi 1-2 (TR)/1-2.2. Stance thiếu rõ ràng, cụ thể.json` |
| `2. Multiple Choice - Multiple.json` | 3 | `faulty_reference_substitution_and_ellipsis` | CC07 | `repetitive_language_structure` | `sample_06` | `Nhóm lỗi 2 (CC)/2.5. Có từ hoặc cấu trúc câu bị lặp lại nhiều lần.json` |
| `3. Choose From List.json` | 1 | `word_choice` | LR03 | `inappropriate_word_choice` | `env_lr_12` | `Nhóm lỗi 3 (LR)/3.2. Sử dụng từ vựng không phù hợp với ngữ cảnh.json` |
| `3. Choose From List.json` | 2 | `article` | GRA06 | `article_number_error` | `gra_ane_02` | `Nhóm lỗi 4 (GRA)/4.3. Lỗi mạo từ, danh từ số nhiều số ít.json` |
| `3. Choose From List.json` | 3 | `word_choice` | LR03 | `inappropriate_word_choice` | `env_lr_05` | `Nhóm lỗi 3 (LR)/3.2. Sử dụng từ vựng không phù hợp với ngữ cảnh.json` |
| `4. Gap Filling.json` | 1 | `subject_verb_agreement` | GRA02 | `verb_form_error` | `sample_03` | `Nhóm lỗi 4 (GRA)/4.2. Chia động từ sai.json` |
| `4. Gap Filling.json` | 2 | `missing_or_inaccurate_connector` | CC05 | `inappropriate_linking_device` | `env_gf_01` | `Nhóm lỗi 2 (CC)/2.3. Công cụ liên kết không phù hợp với mối quan hệ giữa 2 thông tin.json` |
| `4. Gap Filling.json` | 3 | `conditional_and_hypothetical_structure` | GRA14 | `complex_structure_error` | `env_gf_06` | `Nhóm lỗi 4 (GRA)/4.6. Lỗi sai cấu trúc ngữ pháp (Câu điều kiện, câu bị động, cấu trúc so sánh, mệnh đề quan hệ, mệnh đề quan hệ rút gọn, mệnh đề phân từ, eitherneitherwhetherif).json` |
| `5. Annotation.json` | 1 | `word_class` | GRA05 | `word_form_error` | `sample_06` | `Nhóm lỗi 4 (GRA)/4.4. Lỗi từ loại.json` |
| `5. Annotation.json` | 2 | `inaccurate_reporting_of_visual_information` | TA03 | `inaccurate_data_support` | `inaccurate_data_env_03` | `Nhóm lỗi 1-1 (TA)/1-1.4. Đề cập sai dữ liệu của các chi tiết.json` |
| `5. Annotation.json` | 3 | `off_topic_or_topic_shift` | TR02 | `inconsistent_argument` | `env_an_02` | `Nhóm lỗi 1-2 (TR)/1-2.4. Luận điểm không phù hợp (lạc đề).json` |
| `6. Reorder.json` | 1 | `multiple_central_topics_in_one_paragraph` | CC03 | `disorganized_structure` | `env_ro_02` | `Nhóm lỗi 2 (CC)/2.1. Kết cấu bài viết lộn xộn.json` |
| `6. Reorder.json` | 2 | `multiple_central_topics_in_one_paragraph` | CC03 | `disorganized_structure` | `env_ro_01` | `Nhóm lỗi 2 (CC)/2.1. Kết cấu bài viết lộn xộn.json` |
| `6. Reorder.json` | 3 | `multiple_central_topics_in_one_paragraph` | CC03 | `disorganized_structure` | `env_ro_03` | `Nhóm lỗi 2 (CC)/2.1. Kết cấu bài viết lộn xộn.json` |
| `7. Short Writing.json` | 1 | `tense` | GRA01 | `inappropriate_tense_structure` | `env_sw_07` | `Nhóm lỗi 4 (GRA)/4.5. Lựa chọn thìcấu trúc không phù hợp.json` |
| `7. Short Writing.json` | 2 | `limited_grammatical_range` | GRA19 | `limited_sentence_variety` | `env_sw_05` | `Nhóm lỗi 4 (GRA)/4.1. Giới hạn về kiểu câu (chủ yếu là câu đơn).json` |
| `7. Short Writing.json` | 3 | `collocation` | LR04 | `collocation_error` | `sample_02` | `Nhóm lỗi 3 (LR)/3.3. Sử dụng sai collocation.json` |

Ghi chú:
- Choose From List chỉ có 2 lỗi trong repo gốc; Reorder chỉ có 1 lỗi.
- Dạng bài lấy theo `meta.type` trong JSON gốc. Long Writing (dạng 8) không được đưa vào.
- `error_code` đã được chuyển sang danh sách lỗi mới (IELTS_Writing_Error_Codes_2.xlsx), ghi theo tên lỗi dạng snake_case; mã được chọn theo reference trong `input` của từng bài.
