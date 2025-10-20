


a. Các s? ki?n chính trong m?t Sprint


Trong Scrum, m?t Sprint (ch?ng nu?c rút) ch?a d?ng 4 s? ki?n chính (events) d? t?o ra s? thanh tra (inspection) và thích ?ng (adaptation).

	1.
Sprint Planning (L?p k? ho?ch Sprint)


		M?c dích: Ðây là s? ki?n b?t d?u Sprint. Toàn b? Nhóm Scrum (Scrum Team) h?p tác d? lên k? ho?ch cho công vi?c s? du?c th?c hi?n trong Sprint. Bu?i h?p này tr? l?i hai câu h?i:


			1. Cái gì (What): Product Owner trình bày các m?c (User Stories) quan tr?ng nh?t t? Product Backlog. Nhóm s? th?o lu?n và ch?n ra nh?ng m?c mà h? tin r?ng có th? hoàn thành trong Sprint này d? d?t du?c M?c tiêu Sprint (Sprint Goal).


			2. Nhu th? nào (How): Các Nhà phát tri?n (Developers) lên k? ho?ch chi ti?t, chia nh? các User Stories dã ch?n thành các tác v? (tasks) k? thu?t c? th? d? hoàn thành chúng.


	2. Daily Scrum (H?p Scrum H?ng ngày)
		

M?c dích: Là m?t bu?i h?p ng?n (t?i da 15 phút) di?n ra m?i ngày cho các Nhà phát tri?n. M?c dích là d? ki?m tra ti?n d? hu?ng t?i M?c tiêu Sprint và di?u ch?nh k? ho?ch (Sprint Backlog) cho 24 gi? t?i. Nhóm s? chia s? thông tin, d?ng b? hóa công vi?c và xác d?nh các tr? ng?i (impediments) dang c?n tr? h?.

	3. 
Sprint Review (So k?t Sprint)


		M?c dích: Ðu?c t? ch?c vào cu?i Sprint. Nhóm Scrum trình bày Ph?n tang tru?ng (Increment) – t?c là s?n ph?m "có th? dùng du?c" mà h? dã hoàn thành – cho các bên liên quan (Stakeholders) và Product Owner. M?c dích là d? thu th?p ph?n h?i v? s?n ph?m, và d?a trên ph?n h?i dó, Product Owner có th? di?u ch?nh l?i Product Backlog cho các Sprint tuong lai.

	4. 
Sprint Retrospective (C?i ti?n Sprint)


		M?c dích: Ðây là s? ki?n cu?i cùng trong Sprint, di?n ra sau Sprint Review. Toàn b? Nhóm Scrum (bao g?m Product Owner, Scrum Master và Developers) nhìn l?i toàn b? Sprint v?a qua. H? th?o lu?n xem di?u gì dã làm t?t, di?u gì chua t?t, và dua ra m?t k? ho?ch hành d?ng c? th? d? c?i ti?n quy trình làm vi?c c?a chính h? trong Sprint ti?p theo.



b. Ho?t d?ng Sprint Planning cho User Story "T?o ghi chú m?i"

Gi? s? nhóm c?a b?n b?t d?u bu?i Sprint Planning và Product Owner dua ra User Story: "Là m?t ngu?i dùng, tôi mu?n t?o m?t ghi chú m?i". Các ho?t d?ng chính di?n ra nhu sau:



1.Product Owner trình bày (What):


	Product Owner (PO) gi?i thích t?m quan tr?ng c?a tính nang này (ví d?: "Ðây là ch?c nang c?t lõi c?a ?ng d?ng").


	PO s? trình bày các Tiêu chí Ch?p nh?n (Acceptance Criteria - AC), ví d?:


		"Khi nh?n vào nút 'T?o m?i', m?t màn hình so?n th?o tr?ng xu?t hi?n."
		

"Ngu?i dùng có th? nh?p tiêu d? và n?i dung."

		"Ghi chú m?i ph?i du?c t? d?ng luu."


2.
Nhóm làm rõ yêu c?u:
	

Các Nhà phát tri?n (Developers) s? d?t câu h?i cho PO d? làm rõ m?i th?c m?c, ví d?:
		

"Nút 'T?o m?i' n?m ? dâu trên giao di?n?"


		"Khi 't? d?ng luu', h? th?ng luu bao lâu m?t l?n?"
		

"Tiêu d? có b? gi?i h?n ký t? không?"



4.Nhóm phân rã công vi?c (How):
	

Ðây là ph?n quan tr?ng nh?t. Các Developers s? th?o lu?n và chia nh? User Story này thành các tác v? (tasks) k? thu?t c? th?. Ví d?:
		

Task 1 (Frontend): Thi?t k? nút "T?o m?i" (d?u c?ng) trên giao di?n chính.
		

Task 2 (Frontend): T?o màn hình (component) so?n th?o ghi chú (g?m ô Tiêu d? và ô N?i dung).
		

Task 3 (Backend): Vi?t API (ví d?: POST /api/notes) d? nh?n d? li?u và luu ghi chú m?i vào co s? d? li?u.
		

Task 4 (Database): C?p nh?t/thi?t k? b?ng Notes trong co s? d? li?u (thêm c?t title, content, created_at...).
		

Task 5 (Testing): Vi?t k?ch b?n ki?m th? (Test Case) cho ch?c nang t?o ghi chú.



4. Nhóm u?c lu?ng (Estimation):


	Các Developers s? cùng nhau u?c lu?ng "d? l?n" ho?c "n? l?c" (effort) c?n thi?t d? hoàn thành toàn b? User Story này (bao g?m t?t c? các task). H? có th? dùng Story Points (ví d?: "Story này là 3 di?m") ho?c u?c lu?ng th?i gian (ví d?: "C?n kho?ng 16 gi? làm vi?c d? hoàn thành").

5. 

Ðua vào Sprint Backlog:


	Sau khi u?c lu?ng, n?u nhóm d?ng ý r?ng h? có d? kh? nang hoàn thành User Story này trong Sprint, h? s? chính th?c "cam k?t" (commit) và chuy?n nó t? Product Backlog vào Sprint Backlog. Các task k? thu?t (Task 1-5) s? tr? thành danh sách công vi?c c?a nhóm trong Sprint.