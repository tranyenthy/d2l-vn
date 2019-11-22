> # Preface

# Lời nói đầu

> Just a few years ago, there were no legions of deep learning scientists
> developing intelligent products and services at major companies and startups.
> When the youngest of us (the authors) entered the field,
> machine learning didn't command headlines in daily newspapers.
> Our parents had no idea what machine learning was,
> let alone why we might prefer it to a career in medicine or law.
> Machine learning was a forward-looking academic discipline
> with a narrow set of real-world applications.
> And those applications, e.g. speech recognition and computer vision,
> required so much domain knowledge that they were often regarded
> as separate areas entirely for which machine learning was one small component.
> Neural networks, the antecedents of the deep learning models
> that we focus on in this book, were regarded as outmoded tools.

Chỉ một vài năm trước, không có nhiều khoa học học sâu phát triển các sản phẩm
và dịch vụ thông minh tại các công ty lớn và công ty khởi nghiệp. Khi người trẻ
nhất trong nhóm tác giả chúng tôi tiến vào lĩnh vực này, học máy còn chưa xuất
hiện thường xuyên trên truyền thông. Cha mẹ chúng ta không biết học máy là gì,
chứ chưa nói đến việc họ theo đuổi lĩnh vực này thay vị y khoa hay luật khoa.
Học máy từng là một lĩnh vực nghiên cứu <> với một tập nhỏ các ứng dụng thực tê.
Và những ứng dụng đó, chẳng hạn nhận dạng giọng nói hay thị giác máy tính, đòi
hỏi quá nhiều kiến thức ngành khiến chúng thường được phân thành các lĩnh vực
hoàn toàn riêng, ở đó học máy chỉnh là một thành phần nhỏ. Các mạng neuron, tiền đề
của các mô hình học sâu mà chúng ta tập trung vào trong cuốn sách này, từng được
coi là các công cụ lỗi thời.

> In just the past five years, deep learning has taken the world by surprise,
> driving rapid progress in fields as diverse as computer vision,
> natural language processing, automatic speech recognition,
> reinforcement learning, and statistical modeling.
> With these advances in hand, we can now build cars that drive themselves
> (with increasing autonomy), smart reply systems that anticipate mundane replies,
> helping people dig out from mountains of email,
> and software agents that dominate the world's best humans at board games like Go,
> a feat once deemed to be decades away.
> Already, these tools are exerting a widening impact,
> changing the way movies are made, diseases are diagnosed,
> and playing a growing role in basic sciences -- from astrophysics to biology.
> This book represents our attempt to make deep learning approachable,
> teaching you both the *concepts*, the *context*, and the *code*.

Trong chỉ khoảng năm năm gần đây, học sâu đã "làm chủ" thế giới bằng những sự bất
ngờ, dẫn đường cho những tiến triển nhanh chóng trong nhiều lĩnh vực khác nhau như
thị giác máy tính, xử lý ngôn ngữ tự nhiên, nhận dạng giọng nói tự động, học
tăng cường, và mô hình hoá thống kê. Với những tiến bộ này, chúng ta bây giờ có thể
xây dựng xe tẹ lái (với lượng tự động ngày càng cao), hệ thống trả lời tự động,
giúp con người đào sâu vào cả núi email, và các phần mềm chiến thắng nhiều người
giỏi nhất trong các môn cờ như cờ vây, một kỳ tích từng được xem là không thể trong
nhiều thập kỷ tới. Những công cụ này đã và đang gây ảnh hưởng rộng rãi, thay đổi
cách tạo ra các bộ phim, cách chẩn đoán bệnh, đóng một vài trò ngày càng tăng
trong các ngành khoa học cơ bản -- từ vật lý thiên văn tới sinh học. Cuốn sách này được
viết với mong muốn học sâu dễ tiếp cận hơn, dạy bạn từ *khái niệm*, *văn cảnh*, tới
*lập trình*.

> ## About This Book

## Về cuốn sách này

> ### One Medium Combining Code, Math, and HTML

### Một tài liệu bao gồm Code, Toán, và HTML

> For any computing technology to reach its full impact,
> it must be well-understood, well-documented, and supported by
> mature, well-maintained tools.
> The key ideas should be clearly distilled,
> minimizing the onboarding time needing to bring new practitioners up to date.
> Mature libraries should automate common tasks,
> and exemplar code should make it easy for practitioners
> to modify, apply, and extend common applications to suit their needs.
> Take dynamic web applications as an example.
> Despite a large number of companies, like Amazon,
> developing successful database-driven web applications in the 1990s,
> the full potential of this technology to aid creative entrepreneurs
> has only been realized over the past ten years,
> owing to the development of powerful, well-documented frameworks.

Với bất kỳ kỹ thuật tính toán nào để đạt được ảnh hưởng đầy đủ của nó, nó phải dễ
hiểu, có tài liệu đầy đủ, và được hỗ trợ bởi nhưng công cụ cấp tiến được "bảo trì"
thường xuyên. Các ý tưởng chính cần được chắt lọc rõ ràng, tối thiểu thời gian
chuẩn bị cần thiết để trang bị kiến thức cập nhật cho những người mới bắt đầu.
Các thư viện cấp tiến nên tự động hoá các tác vụ đơn giản, và các đoạn code ví dụ
cần phải đơn giản cho những người mới bắt đầu dễ chỉnh sửa, ứng dụng, và mở rộng
những ứng dụng thông thường tới các ứng dụng họ cần. Lấy các ứng dụng trang web
động làm ví dụ. Mặc dù các công ty công nghệ lớn, như Amazon, phát triển thành
công các ứng dụng web định hướng bởi cơ sở dữ liệu từ nhưng năm 1990, tiềm năng của công
nghệ này để hỗ trợ các doanh nghiệp sáng tạo chỉ được nhận ra từ khoảng mười năm nay,
nhờ vào sự phát triển của các nền tảng mạnh mẽ và với tài liệu đầy đủ.

> Realizing deep learning presents unique challenges because
> any single application brings together various disciplines.
> Applying deep learning requires simultaneously understanding
> (i) the motivations for casting a problem in a particular way,
> (ii) the mathematics of a given modeling approach,
> (iii) the optimization algorithms for fitting the models to data,
> (iv) and the engineering required to train models efficiently,
> navigating the pitfalls of numerical computing and getting the most
> out of available hardware.
> Teaching both the critical thinking skills required to formulate problems,
> the mathematics to solve them, and the software tools to implement those
> solutions all in one place presents formidable challenges.
> Our goal in this book is to present a unified resource
> to bring would-be practitioners up to speed.

Nhận thấy học sâu mang những thách thức riêng biệt vì bất kỳ ứng dụng riêng lẻ
nào cũng bao gồm nhiều lĩnh vực khác nhau. Ứng dụng học sâu đòi hỏi những hiểu
biết đồng thời về (i) động lực để đưa ra một vấn đề theo một hướng cụ thể, (ii) toán
học cho một hướng mô hình hoá, (iii) những thuật toán tối ưu cho việc khớp mô hình
với dữ liệu, và (iv) phần kỹ thuật yêu cầu để huấn luyện mô hình một cách hiệu quả,
xử lý những khó khăn trong tính toán và tận dụng thật tốt phần cứng hiện có. Đào
tạo kỹ năng suy nghĩ thấu đáo cần thiết để định hình bài toán, kiến thức toán để
giải chúng, và các công cụ phần mềm để triển khai những giải pháp đó tất cả trong một
hàm chứa nhiều thách thức lớn. Mục tiêu của chúng tôi trong cuốn sách này là trình
bày một nguồn tài liệu tổng hợp giúp những học viên nhanh chóng tiếp cận.

> We started this book project in July 2017
> when we needed to explain MXNet's (then new) Gluon interface to our users.
> At the time, there were no resources that were simultaneously
> (1) up to date, (2) covered the full breadth of modern machine learning
> with anything resembling of technical depth,
> and (3) interleaved the exposition one expects from an engaging textbook
> with the clean runnable code one seeks in hands-on tutorials.
> We found plenty of code examples for how to use a given deep learning
> framework (e.g. how to do basic numerical computing with matrices in TensorFlow)
> or for implementing particular techniques (e.g. code snippets for LeNet, AlexNet, ResNets, etc)
> in the form of blog posts or on GitHub.
> However, these examples typically focused on
> *how* to implement a given approach,
> but left out the discussion of *why* certain algorithmic decisions are made.
> While sporadic topics have been covered in blog posts,
> e.g. on the website [Distill](http://distill.pub) or personal blogs,
> they only covered selected topics in deep learning, and often lacked associated code.
> On the other hand, while several textbooks have emerged,
> most notably :cite:`Goodfellow.Bengio.Courville.2016`,
> which offers an excellent survey of the concepts behind deep learning,
> these resources don't marry the descriptions to realizations of the concepts in code,
> sometimes leaving readers clueless as to how to implement them.
> Moreover, too many resources are hidden behind the paywalls of commercial course providers.

Chúng tôi bắt đầu dự án sách này từ tháng 7/2017 khi chugns tôi cần giải thích 
giao diện MXNet (khi đó còn mới) Gluon tới người dùng. Tại thời điểm đó, không có
một nguồn tài liệu nào vừa đồng thời (1) cập nhật, (2) bao gồm đầy đủ các khía
cạnh của học máy hiện đại với đầy đủ chiều sâu kỹ thuật, và (3) xem kẽ các giải
trình mà người ta mong đợi từ một cuốn sách giáo trình với mã có thể thực thi, điều
thường được tìm thấy trong các bài hướng dẫn thực hành. Chúng tôi tìm thấy một lượng
lớn các đoạn mã ví dụ về việc sử dụng một nền tảng học sâu (ví dụ làm thế nào
để thực hiện các phép toán cơ bản với ma trận trên TensorFlow) hoặc để triển khai
những kỹ thuật cụ thể (ví dụ các đoạn mã cho LeNet, AlexNet, ResNet,...) dưới dạng
một bài blog hoặc trên GitHub. Tuy nhiên, những ví dụ này thường tập trung vào khía
cạnh *làm thế nào* để triển khai một hướng tiếp cận cho trước, mà bỏ qua các thảo luận
về việc *tại sao* một thuật toán được tạo như thế. 
Trong khi các chủ đề lẻ tẻ đã được đề cập trong các bài đăng trên blog, ví dụ trên
trang web [Distill](http://distill.pub) hoặc các blog cá nhân, họ chỉ đề cập
đến một vài chủ đề được chọn về học sâu, và thường thiếu mã đi kèm. Một mặt khác,
trong khi nhiều sách giáo trình đã ra đời, đáng chú ý nhất là
:cite:`Goodfellow.Bengio.Courville.2016` (cuốn này cung cấp một bản khảo sát xuất
sắc về các khái niệm phía sau học sâu), những nguồn tài liệu này lại không đi kèm
với việc diễn giải dưới dạng mã để hiểu rõ hơn về các khái niệm.

> We set out to create a resource that could
> (1) be freely available for everyone,
> (2) offer sufficient technical depth to provide a starting point on the path
> to actually becoming an applied machine learning scientist,
> (3) include runnable code, showing readers *how* to solve problems in practice,
> and (4) that allowed for rapid updates, both by us, and also by the community at large,
> and (5) be complemented by a [forum](http://discuss.mxnet.io)
> for interactive discussion of technical details and to answer questions.

Chúng tôi đặt mục tiêu tạo ra một tài liệu mà có thể (1) miễn phí cho mọi người,
(2) cung cấp chiều sâu kỹ thuật đầy đủ tạo điểm bắt đầu cho con đường trở thành
một nhà khoa học học máy ứng dụng, (3) bao gồm mã thực thi được, trình bày cho
người đọc *làm thế nào* giải quyết các bài toán trên thực tế, và (4) tài liệu này
có thể cập nhật một cách nhanh chóng, bằng cả chúng tôi và cộng động ở quy mô lớn, và (5)
được bổ sung bởi một [diễn đàn](http://discuss.mxnet.io) cho những thảo luận
nhanh chóng các chi tiết kỹ thuật và hỏi đáp.

> These goals were often in conflict.
> Equations, theorems, and citations are best managed and laid out in LaTeX.
> Code is best described in Python.
> And webpages are native in HTML and JavaScript.
> Furthermore, we want the content to be
> accessible both as executable code, as a physical book,
> as a downloadable PDF, and on the internet as a website.
> At present there exist no tools and no workflow
> perfectly suited to these demands, so we had to assemble our own.
> We describe our approach in detail in :numref:`chapter_contribute`.
> We settled on Github to share the source and to allow for edits,
> Jupyter notebooks for mixing code, equations and text,
> Sphinx as a rendering engine to generate multiple outputs,
> and Discourse for the forum.
> While our system is not yet perfect, these choices provide a good compromise
> among the competing concerns.
> We believe that this might be the first book published using such an integrated workflow.

Những mục tiêu này từng có xung đột. Các công thức, định lý, và các trích dẫn
được quản lý tốt nhất trên LaTex. Mã được giải thích tốt nhất bằng Python. Và
trang web phù hợp với HTML và JavaScript. Hơn nữa, chúng tôi muốn nội dung vừa
có thể truy cập được bằng mã có thể thực thi, bằng một cuốn sách như một tệp tin
PDF tải về được, và ở trên internet như một trang web. Hiện tại không tồn tại công cụ
nào phù hợp một cách hoàn hảo cho những nhu cầu này, bởi vậy chúng tôi phải tự tạo công cụ
cho riêng mình. Chúng tôi mô tả hướng tiếp cận một cách chi tiết trong :numref:`chapter_contribute`.
Chúng tôi tổ chức dự án trên GitHub để chia sẻ mã nguồn và cho phép sửa đổi, Jupyter notebook để
kết hợp mã, các phương trình và nội dung chữ, Sphinx như một bộ máy tạo nhiều tệp tin đầu ra,
và Discourse để tạo diễn đàn. Trong khi hệ thống này còn chưa hoàn hảo, những
sự lựa chọn này cung cấp một giải pháp chấp nhận được trong số các giải pháp
tương tự. Chúng tôi tin rằng đây có thể là cuốn sách đầu tiên được xuất bản dưới
dạng kết hợp này.

> ### Learning by Doing

### Học bằng Thực hành

> Many textbooks teach a series of topics, each in exhaustive detail.
> For example, Chris Bishop's excellent textbook :cite:`Bishop.2006`,
> teaches each topic so thoroughly, that getting to the chapter
> on linear regression requires a non-trivial amount of work.
> While experts love this book precisely for its thoroughness,
> for beginners, this property limits its usefulness as an introductory text.

Rất nhiều sách giáo trình hướng dẫn một chuỗi các chủ đề, mỗi chủ đề đều rất
chi tiết. Ví dụ, cuốn giáo trình xuất sắc của Chris Bishop :cite:`Bishop.2006`, dạy
mỗi chủ đề một cách kỹ càng, khiến việc tới chương hồi quy tuyến tính đòi hỏi 
một lượng kiến thức không nhỏ. Trong khi các chuyên gia yêu thích cuốn sách này vì tính
cặn kẽ của nó, cho nhưng người mới bắt đầu, tính chất này giới hạn tính hữu dụng của nó
như một tài liệu giới thiệu.

> In this book, we'll teach most concepts *just in time*.
> In other words, you'll learn concepts at the very moment
> that they are needed to accomplish some practical end.
> While we take some time at the outset to teach
> fundamental preliminaries, like linear algebra and probability.
> We want you to taste the satisfaction of training your first model
> before worrying about more esoteric probability distributions.

Trong cuốn sách này, chúng tôi sẽ hướng dẫn hầu hết các khái niệm *vừa đủ*.
Nói cách khác, bạn sẽ học những khái niệm đúng lúc chúng cần để rút ra được bài học
thực tế. Trong khi chúng tôi dành thời gian để hướng dẫn các khái niệm sơ bộ nền tảng,
như đại số tuyến tính và xác suất, chúng tôi mong muốn bạn tận hưởng cảm giác
thoả mãn khi huấn luyện mô hình đầu tiên trước khi lo lắng về nhứng phân phối xác suất phức tạp.


> Aside from a few preliminary notebooks that provide a crash course
> in the basic mathematical background,
> each subsequent notebook introduces both a reasonable number of new concepts
> and provides a single self-contained working example -- using a real dataset.
> This presents an organizational challenge.
> Some models might logically be grouped together in a single notebook.
> And some ideas might be best taught by executing several models in succession.
> On the other hand, there's a big advantage to adhering
> to a policy of *1 working example, 1 notebook*:
> This makes it as easy as possible for you to
> start your own research projects by leveraging our code.
> Just copy a notebook and start modifying it.

Ngoài một vài notebook cung cấp khái niệm cơ bản về nền tảng toán, mỗi notebook vừa giới thiệu
một lượng hợp lý các khái niệm vừa cung cấp một ví dụ đơn giản khép kín -- sử dụng một tập dữ liệu
thực tế. Việc này thể hiện một thách thức về mặt tổ chức nội dung. Một vài mô hình có thể
được gộp với nhau một cách logic trong chỉ một notebook, trong khi các ý tưởng khác cần
phải được diễn giải trong một chuỗi các mô hình. Ở một khía cạnh khác, có một ưu
điểm lớn của việc bám vào nguyên tắc *một ví dụ chạy được, một notebook*: Việc này
khiến bạn dễ dàng bắt đầu với các dự án nghiên cứu của chính mình bằng cách tận dụng
mã của chúng tôi. Chỉ cần sao chép một notebook và bắt đầu chỉnh sửa nó.

> We will interleave the runnable code with background material as needed.
> In general, we will often err on the side of making tools
> available before explaining them fully (and we will follow up by
> explaining the background later).
> For instance, we might use *stochastic gradient descent*
> before fully explaining why it is useful or why it works.
> This helps to give practitioners the necessary
> ammunition to solve problems quickly,
> at the expense of requiring the reader to trust us with some curatorial decisions.

Chúng tôi sẽ xen kẽ mã thực thi được và kiến thức nền tảng khi cần thiết. Nhìn chung, chúng tôi sẽ
thường xuyên <>. Chẳng hạn, chúng tôi sẽ sử dụng *trượt gradient ngẫu nhiên* trước khi
giải thích căn kỹ tại sao nó hữu ích hay tại sao nó hoạt động. Việc này giúp cung
cấp cho những người thực hành công cụ "đạn dược" cần thiết để giải quyết các vấn đề
một cách nhanh chóng, đổi lại, người đọc cần tin tưởng những sự lựa chọn của chúng tôi.


> Throughout, we'll be working with the MXNet library,
> which has the rare property of being flexible enough for research
> while being fast enough for production.
> This book will teach deep learning concepts from scratch.
> Sometimes, we want to delve into fine details about the models
> that would typically be hidden from the user by ``Gluon``'s advanced abstractions.
> This comes up especially in the basic tutorials,
> where we want you to understand everything that happens in a given layer or optimizer.
> In these cases, we'll often present two versions of the example:
> one where we implement everything from scratch,
> relying only on NDArray and automatic differentiation,
> and another, more practical example, where we write succinct code using ``Gluon``.
> Once we've taught you how some component works,
> we can just use the ``Gluon`` version in subsequent tutorials.

Chúng ta sẽ làm việc với thư viện MXnet với đặc tính hiếm hoi của việc vừa đủ linh động cho nghiên
cứu vừa giúp nhanh chóng tạo ra sản phẩm. Cuốn sách này sẽ dạy các khái niệm học sâu từ sơ khởi. Thi
thoảng, chúng tôi muốn đi sâu vào chi tiết của mô hình, điều mà thông thường được ẩn đi dưới các
tóm tắt có phần nâng cao của ``Gluon``. Điều này xuất hiện đặc biệt trong các bài hướng dẫn cơ bản,
ở đó chugns tôi muốn bạn hiểu mọi thứ xuất hiện trong một tầng mô hình hoặc bộ tối ưu cụ thể. Trong
những trường hợp này chúng tôi sẽ thường trình bày hai phiên bản của một ví dụ: một bản mà mọi thứ
được thiết kế từ sơ khởi, chỉ phụ thuộc vào NDArry và đạo hàm tự động; bản còn lại, là một ví dụ
thực tế hơn, được viết với mã xúc tích hơn sử dụng ``Gluon``. Một khi chúng tôi đã hướng dẫn bạn
một thành phần nào đó hoạt động như thế nào, chúng tôi sẽ chỉ dùng phiên bản ``Gluon`` trong những
bài hướng dẫn tiếp theo.


> ### Content and Structure

### Nội dung và Cấu trúc

> The book can be roughly divided into three parts, which are presented by different colors in :numref:`fig_book_org`:

Cuốn sách này có thể chia làm ba phần, được biểu diẽn bởi các màu khác nhau trong :numref:`fig_book_org`:

> ![Book structure](../img/book-org.svg)

![Cấu trúc cuốn sách](../img/book-org.svg)
:label:`fig_book_org`


> * The first part covers prerequisites and basics.  The first chapter offers an
> introduction to deep learning in :numref:`chapter_introduction`.  In
> :numref:`chapter_crashcourse`, we'll quickly bring you up to speed on the
> prerequisites required for hands-on deep learning, such as how to acquire and
> run the codes covered in the book.  :numref:`chapter_linear` and
> :numref:`chapter_perceptrons` cover the most basic concepts and techniques of deep
> learning, such as linear regression, multi-layer perceptrons and regularization.
<!--If you are short on time or you only want to learn only
about the most basic concepts and techniques of deep learning,
it is sufficient to read the first section only.-->

* Phần đầu tiên bao gồm các kiến thức tiên quyết và cơ bản. Chương đầu tiên cung cấp một bài giới
thiệu về học sâu tại :numref:`chapter_introduction`. Trong :numref:`chapter_crashcourse`, chúng tôi
sẽ nhanh chóng cung cấp các kiến thức tiên quyết cần thiết cho thực hành học sâu, chẳng hạn làm thế nào để lấy và chạy mã được cho trong cuốn sách. :numref:`chapter_linear` và
và :numref:`chapter_perceptrons` bao gồm những khái niệm và kỹ thuật cơ bản nhất của học sâu, như
hồi quy tuyến tính, tri giác đa tầng và regularization.

> * The next four chapters focus on modern deep learning techniques.
> :numref:`chapter_computation` describes the various key components of deep
> learning calculations and lays the groundwork for the later implementation of
> more complex models.  Next we explain in :numref:`chapter_cnn` and
> :numref:`chapter_modern_cnn`, powerful tools that form the backbone of most
> modern computer vision systems in recent years.  Subsequently, we introduce
> :numref:`chapter_rnn` models that exploit temporal or sequential structure in
> data, and are commonly used for natural language processing and time series
> prediction. :numref:`chapter_attention` introduces recent models exploring the
> attention mechanism.  These sections will get you up to speed on the basic tools
> behind most modern deep learning.

* Bốn chương tiếp theo tập trung vào các kỹ thuật học sâu hiện đại. :numref:`chapter_computation`
mô tả các thành phần chính khác nhau của tính toán trong học sâu và đặt nền móng cho cách triển
khai của các mô hình phức tạp hơn về sau. Tiếp theo chúng tôi giải thích trong :numref:`chapter_cnn`
và :numref:`chapter_modern_cnn` các công cụ hữu ích là xương sống của hầu hết các hệ thống thị
giác máy tính trong những năm gần đây. Tiếp theo đó, chúng tôi giới thiệu mô hình :numref:`chapter_rnn`, mô hình này khai kthác cấu trúc dạng chuỗi hoặc thời gian trong dữ liệu,
và thường được dùng trong xử lý ngôn ngữ tự nhiên và dự đoán chuỗi thời gian. :numref:`chapter_attention` giới thiệu các mô hình gần đây khai phá cơ chế chú ý. Những mục này sẽ
trang bị cho bạn những công cụ cơ bản đằng sau học sâu hiện đại một cách nhanh chóng.

> * Part three discusses scalability, efficiency and applications.  First we
> discuss several common :numref:`chapter_optimization` used to train deep
> learning models.  The next chapter, :numref:`chapter_performance` examines
> several important factors that affect the computational performance of your deep
> learning code.    :numref:`chapter_cv` and :numref:`chapter_nlp` illustrate major
> applications of deep learning in computer vision and natural language
> processing, respectively. Finally, :numref:`chapter_gans` presents an emerging family of models called generative adversarial networks.

* Phần ba thảo luận về khả năng nhân rộng, tính hiệu quảc và ứng dụng. Trước hết chúng tôi thảo
luận nhiều :numref:`chapter_optimization` chung được sử dụng để huấn luyện các mô hình học sâu.
Chương tiếp theo, :numref:`chapter_performance` kiểm định nhiều nhân tố quan trọng ảnh hưởng tới
hiệu năng tính toán của mã học sâu của bạn. :numref:`chapter_cv` và :numref:`chapter_nlp` lần lượt
mô tả các ứng dụng chính của học sâu trong thị giác máy tính và xử lý ngôn ngữ tự nhiên. Cuối cùng,
:numref:`chapter_gans` trình bày một nhóm đang nổi bật của các mô hình được gọi là <GAN>.

> ### Code

### Mã nguồn 
:label:`chapter_code`

> Most sections of this book feature executable code.
> We recognize the importance of an interactive learning experience in deep learning.
> At present certain intuitions can only be developed through trial and error,
> tweaking the code in small ways and observing the results.
> Ideally, an elegant mathematical theory might tell us
> precisely how to tweak our code to achieve a desired result.
> Unfortunately, at present such elegant theories elude us.
> Despite our best attempts, our explanations for of various techniques might be lacking,
> sometimes on account of our shortcomings,
> and equally often on account of the nascent state of the science of deep learning.
> We are hopeful that as the theory of deep learning progresses,
> future editions of this book will be able to provide insights in places the present edition cannot.

Hầu hết các phần của cuốn sách này chứ mã có thể thực thi. Chúng tôi nhận ra tầm quan trọng của
trải nghiệm học tương tác trong học sâu. Tại thời điểm này các trực giác cụ thể chỉ có thể phát
triển thông qua thử và sai, điều chỉnh mã một cách tối giản và quan sát kết quả. Một cách lý tưởng,
một lý thmuốn toán học có thể chỉ cho chúng ta một cách chính xác cách điều chỉnh mã để đạt được kết
quả mong muốn. Thật không may, hiện tại lý thuyết tao nhã đó còn xa mời. Mặc dù đã rất cố gắng, các
giải thích của chúng tôi về nhiều kỹ thuật có thể còn thiếu hoàn chỉnh, đôi khi bởi những thiếu sót
của chúng tôi, và đôi khi bởi sự non trẻ của ngành khoa học học sâu. Chúng tôi hy vọng rằng khi lý
thuyết về học sâu tiến triển hơn, những lần tái bản tiếp theo có khả năng cung cấp những cái nhìn
sâu sắc mà lần xuất bản này chưa có được.

> Most of the code in this book is based on Apache MXNet.
> MXNet is an open-source framework for deep learning
> and the preferred choice of AWS (Amazon Web Services),
> as well as many colleges and companies.
> All of the code in this book has passed tests under the newest MXNet version.
> However, due to the rapid development of deep learning,
> some code *in the print edition* may not work properly in future versions of MXNet.
> However, we plan to keep the online version remain up-to-date.
> In case of such problems, please consult :ref:`chapter_installation`
> to update the code and runtime environment.

Hầu hết mã trong cuốn sách này được dựa trên Apache MXNEet. là một nền tảng mã nguồn mở cho học sâu
và là lựa chọn ưu tiên của AWS (Amazon Web Services) cũng như nhiều đồng nghiệp và doanh nghiệp.
Toàn bộ mã nguồn trong cuốn sách đã được kiểm chứng trên phiên bản MXNet mới nhất. Tuy nhiên, chúng
tôi có kế hoạch giữ bản online luôn được cập nhật. Nếu có vấn đề liên quan đến phiên bản phần mền,
bạn có thể tham khảo :ref:`chapter_installation` để luôn cập nhật mã và môi trường chạy mã.


> At times, to avoid unnecessary repetition,
> we encapsulate the frequently-imported and referred-to functions, classes, etc.
> in this book in the `d2l` package. For any block block such as a function, a
> class, or multiple imports to be saved in the package, we will mark it with `#
> Save to the d2l package`. For example, these are the packages and modules will
> be used by the `d2l` package.

Để tránh những sự lặp lại không cần thiết, chúng tôi gộp những hàm, lớp, v.v. thường xuyên
được sử dụng trong cuốn sách này vào gói `d2l`. Với bất kể khối mã nào như một hàm số, một lớp,
hay khai báo thư viện được lưu vào trong gói `d2l`, chúng tối sẽ đánh dấu nó bởi
`# Save to the d2l package`. Ví dụ, dưới đây là những gói và mô-đun sẽ được sử dụng trong gói `d2l`.

```{.python .input  n=1}
# Save to the d2l package
from IPython import display
import collections
import os
import sys
import numpy as np
import math
from matplotlib import pyplot as plt
from mxnet import nd, autograd, gluon, init, context, image
from mxnet.gluon import nn, rnn
import random
import re
import time
import tarfile
import zipfile
```

> We give a detailed overview of these functions and classes in :numref:`chapter_d2l`.

Chúng tôi sẽ cung cấp một cái nhìn chi tiết về những hàm và lớp này trong :numref:`chapter_d2l`.

> ### Target Audience

### Đối tượng độc giả

> This book is for students (undergraduate or graduate), engineers, and
> researchers, who seek a solid grasp of the practical techniques of deep
> learning.  Because we explain every concept from scratch, no previous background
> in deep learning or machine learning is required.  Fully explaining the methods
> of deep learning requires some mathematics and programming, but we'll only
> assume that you come in with some basics, including (the very basics of) linear
> algebra, calculus, probability, and Python programming.  Moreover, this book's
> appendix provides a refresher on most of the mathematics covered in this book.
> Most of the time, we will prioritize intuition and ideas over mathematical
> rigor.  There are many terrific books which can lead the interested reader
> further. For instance Linear Analysis by Bela Bollobas :cite:`Bollobas.1999`
> covers linear algebra and functional analysis in great
> depth. All of Statistics :cite:`Wasserman.2013`
> is a terrific guide to statistics.  And if you have not used Python before, you
> may want to peruse the [Python tutorial](http://learnpython.org/).

Cuốn sách này dành cho sinh viên (đại học hoặc cao học), kỹ sư, và nhà nghiên cứu, những người
muốn nắm vững những kỹ thuật thực tế của học sâu. Bởi chúng tôi giải thích mọi khái niệm từ sơ khởi,
cuốn sách này không đòi khỏi nền tảng tiền đề về học sâu và học máy. Giải thích một cách cặn kẽ
các phương pháp trong học sâu đòi hỏi kiến thức về toán và lập trình, nhưng chúng tôi sẽ chỉ giả sử
rằng bạn chỉ cần những kiến thức nền tảng, bao tính (kiến thứ rất cơ bản của) đại số tuyến tính,
phương pháp tính, xác xuất, và lập trình Python. Hơn nữa, mục lục của cuốn sách này cung một cho
người mới bắt đầu hầu hết những kiến thức toán cần thiết. Trong hầu hết các trường hợp, chúng tôi
sẽ ưu tiên trực giác và ý tưởng hơn toán học khô khan. Nếu hứng thú, bạn có thể tham khảo rất nhiều
cuốn sách xuất sắc khác. Ví dụ Linear Analysis bởi Bela Bollobas :cite:`Bollobas.1999` đề cập đại
số tuyến tính và giải tích hàm một cách chuyên sâu. All of Statistics :cite:`Wasserman.2013` là một
bản hướng dẫn xuất sắc cho thống kê. Và nếu bạn chưa dùng Python trước đây, bạn có thể tham khảo
[Python tutorial](http://learnpython.org/).

> ### Forum

### Diễn đàn

> Associated with this book, we've launched a discussion forum,
> located at [discuss.mxnet.io](https://discuss.mxnet.io/).
> When you have questions on any section of the book,
> you can find the associated discussion page by scanning the QR code
> at the end of the section to participate in its discussions.
> The authors of this book and broader MXNet developer community
> frequently participate in forum discussions.

Đi kèm với cuốn sách này, chúng tôi tạo một diễn đàn trao đổi tại
[discuss.mxnet.io](https://discuss.mxnet.io/) (và [diễn đàn tiếng Việt](TODO) do nhóm dịch tạo).
Khi bạn có câu hỏi về bất kỳ phần nào của cuốn sách, bạn có thể tìm các phần thảo luận tương ứng
bằng cách quét mã QR tại cuối của mỗi phần để tham gia thảo luận. Các tác giả của cuốn sách và cộng
động phát triển lớn hơn của MXNet thường xuyên tham gia thảo luận trong diễn đàn này.


> ## Acknowledgments

### Lời cảm ơn

> We are indebted to the hundreds of contributors for both
> the English and the Chinese drafts.
> They helped improve the content and offered valuable feedback.
> Specifically, we thank every contributor of this English draft
> for making it better for everyone.
> Their GitHub IDs or names are (in no particular order):
> alxnorden, avinashingit, bowen0701, brettkoonce, Chaitanya Prakash Bapat,
> cryptonaut, Davide Fiocco, edgarroman, gkutiel, John Mitro, Liang Pu, Rahul Agarwal, mohamed-ali,
> mstewart141, Mike Müller, NRauschmayr, Prakhar Srivastav, sad-, sfermigier, Sheng Zha, sundeepteki,
> topecongiro, tpdi, vermicelli, Vishaal Kapoor, vishwesh5, YaYaB, Yuhong Chen, Evgeniy Smirnov, lgov, Simon Corston-Oliver, IgorDzreyev, trungha-ngx, pmuens, alukovenko, senorcinco, vfdev-5, dsweet, Mohammad Mahdi Rahimi, Abhishek Gupta, uwsd, DomKM, Lisa Oakley, bowen0701, arush15june, prasanth5reddy, brianhendee, mani2106, mtn, lkevinzc, caojilin, Lakshya, Fiete Lüer, Surbhi Vijayvargeeya, Muhyun Kim, dennismalmgren, adursun, Anirudh Dagar, liqingnz, Pedro Larroy, lgov, ati-ozgur, goldmermaid, Jun Wu, Matthias Blume, apeforest, geogunow, Josh Gardner, Maximilian Böther, rislam, Leonard Lausen, Abhinav Upadhyay, rongruosong, Steve Sedlmeyer, ruslo, Rafael Schlatter, liusy182, GIannis Pappas, ruslo, ati-ozgur, qbaza, dchoi77.
> Moreover, we thank Amazon Web Services, especially Swami Sivasubramanian,
> Raju Gulabani, Charlie Bell, and Andrew Jassy for their generous support in writing this book.
> Without the available time, resources, discussions with colleagues,
> and continuous encouragement this book would not have happened.

Chúng tôi nợ lời cảm ơn tới hàng trăm cộng tác viên cho cả bản nháp tiếng Anh và tiếng Trung đã giúp
cải thiện nội dung và cung cấp những phản hồi giá trị. Đặc biệt, chúng tôi cảm ơn mọi cộng tác
viên của bản nháp tiếng Anh này đã mang nó đến mọi người. Tài khoản GitHub hoặc tên (không theo
thứ tự nào) là alxnorden, avinashingit, bowen0701, brettkoonce, Chaitanya Prakash Bapat,
cryptonaut, Davide Fiocco, edgarroman, gkutiel, John Mitro, Liang Pu, Rahul Agarwal, mohamed-ali,
mstewart141, Mike Müller, NRauschmayr, Prakhar Srivastav, sad-, sfermigier, Sheng Zha, sundeepteki,
topecongiro, tpdi, vermicelli, Vishaal Kapoor, vishwesh5, YaYaB, Yuhong Chen, Evgeniy Smirnov, lgov,
Simon Corston-Oliver, IgorDzreyev, trungha-ngx, pmuens, alukovenko, senorcinco, vfdev-5, dsweet,
Mohammad Mahdi Rahimi, Abhishek Gupta, uwsd, DomKM, Lisa Oakley, bowen0701, arush15june, prasanth5reddy, brianhendee, mani2106, mtn, lkevinzc, caojilin, Lakshya, Fiete Lüer, Surbhi Vijayvargeeya, Muhyun Kim, dennismalmgren, adursun, Anirudh Dagar, liqingnz, Pedro Larroy, lgov, ati-ozgur, goldmermaid, Jun Wu, Matthias Blume, apeforest, geogunow, Josh Gardner, Maximilian Böther, rislam, Leonard Lausen, Abhinav Upadhyay, rongruosong, Steve Sedlmeyer, ruslo, Rafael Schlatter, liusy182, GIannis Pappas, ruslo, ati-ozgur, qbaza, dchoi77. Hơn nữa, chúng tôi cảm ơn Amazon Web Services, đặc biệt là Swami Sivasubramanian,
Raju Gulabani, Charlie Bell, và Andrew Jassy vì những hỗ trợ của họ trong việc hoàn thiện cuốn sách này.

> ## Summary

## Tóm tắt 

> * Deep learning has revolutionized pattern recognition, introducing technology that now powers a wide range of  technologies, including computer vision, natural language processing, automatic speech recognition.
> * To successfully apply deep learning, you must understand how to cast a problem, the mathematics of modeling, the algorithms for fitting your models to data, and the engineering techniques to implement it all.
> * This book presents a comprehensive resource, including prose, figures, mathematics, and code, all in one place.
> * To answer questions related to this book, visit our forum at https://discuss.mxnet.io/.
> * Apache MXNet is a powerful library for coding up deep learning models and running them in parallel across GPU cores.
> * Gluon is a high level library that makes it easy to code up deep learning models using Apache MXNet.
> * Conda is a Python package manager that ensures that all software dependencies are met.
> * All notebooks are available for download on GitHub and  the conda configurations needed to run this book's code are expressed in the `environment.yml` file.
> * If you plan to run this code on GPUs, don't forget to install the necessary drivers and update your configuration.

* Học sâu đã nâng tầm nhận dạng vật thể, giới thiệu lý thuyết và nền tảng rất nhiều công nghệ, bao
 gồm thị giác máy tính, xử lý ngôn ngữ tự nhiên, tự động nhận dạng giọng nói.
* Để ứng dụng học sâu một cách thành công, bạn phải học cách biến đổi một vấn đề, nền tảng toán của
 mô hình hoá, những thuật toán khớp mô hình với dữ liệu, và các kỹ thuật thực tế để triển khai chúng.
* Cuốn sách này trình bày một tài nguyên đầy đủ, bao gồm phần chữ, hình vẽ, toán học, và mã nguồn,
 tất cả trong một.
* Để trả lời các câu hỏi liên quan tới cuốn sách, mời bạn tham gia diễn đàn của chúng tôi tại
 https://discuss.mxnet.io/ (hoặc [diễn đàn tiếng Việt] do nhóm dịch tạo).
* Apache MXNet là một thư viện mạnh mẽ cho viết mã mô hình học sâu và chạy chúng song song trên nhiều lõi GPU.
* Gluon là một thư viện cấp cao giúp viết mã các hệ thống học sâu một cách dễ dàng sử dụng Apache MXNet.
* Conda là một bộ quản lý các gói Python đảm bảo đáp ứng mọi gói phần mềm liên quan.
* Mọi notebook có thể tải về miễn phí tại GitHub và cấu hình conda cần thiết để chạy mã trong cuốn sách này được cung cấp trong tệp tin `environment.yml`.
* Nếu bạn có kế hoạch chạy mã này trên GPU, đừng quên cài đặt các driver cần thiết và cập nhật cấu hình của bạn.

> ## Exercises

## Bài tập

> 1. Register an account on the discussion forum of this book [discuss.mxnet.io](https://discuss.mxnet.io/).
> 1. Install Python on your computer.
> 1. Follow the links at the bottom of the section to the forum,
> where you'll be able to seek out help and discuss the book and find answers to your questions
> by engaging the authors and broader community.
> 1. Create an account on the forum and introduce yourself.

1. Đăng ký một tài khoản trên diễn đàn của cuốn sách này tại [discuss.mxnet.io](https://discuss.mxnet.io/) (và [diễn đàn tiếng Việt]() do nhóm dịch tạo).
2. Cài đặt Python trên máy của bạn.
3. Theo đường dẫn tại cuối mỗi phần để vào diễn đàn, nơi bạn có thể tìm sự trợ giúp và thảo luận cuốn sách, và tìm câu trả lời từ các tác giả và cộng đồng lớn hơn.
4. Tạo một tài khoản trên diễn đàn và giới thiệu bản thân.

> ## Scan the QR Code to [Discuss](https://discuss.mxnet.io/t/2311)

## Quét mã QA để [Thảo luận](https://discuss.mxnet.io/t/2311)

![](../img/qr_preface.svg)
