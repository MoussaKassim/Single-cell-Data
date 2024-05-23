<KODAMA>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KODAMA</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* Font Family and Size */
        body,
        .navbar-nav .nav-link {color: #ffffff;
        .navbar-nav .nav-link {
            font-family: "Source Sans Pro", Arial, sans-serif;
            font-size: 16px;
            color: #ffffff;
            background-color: ;
        }}
         
        /* Navbar Styles */
        .navbar {
            position: fixed;
            top: 0;
            left: 0cm;
            right: 0;
            z-index: 500;
            background-color: #333333;
            padding-top: 0;
            padding-bottom: 0;
            height: 50px;
            width: calc(100%);
        }

        .navbar-brand {
            margin-top: -5px;
        }

        .navbar-nav .nav-item {
            margin-bottom: 04px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 109px 109px rgba(0, 0, 0, 0);
        }

        .navbar-nav .nav-link {
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }

        .navbar-nav .nav-item:nth-child(1) {
            margin-top: 20px;
        }

        .navbar-nav .nav-item:nth-child(2) {
            margin-top: 20px;
        }

        .navbar-nav .nav-item:nth-child(3) {
            margin-top: 20px;
        }

        .navbar-nav .nav-item:nth-child(4) {
            margin-top: 20px;
            margin-right: 10cm;
            margin-left: auto;
        }

        .navbar-nav .source-code-link {
            margin-top: 40px;
        }

        .container {
            padding-left: 7.3cm;
        }

        .navbar-brand,
        .navbar-nav .nav-link {
            padding: 0.1px 1rem;
            text-decoration: none;
            display: inline-block;
        }

        .navbar-brand {
            font-size: 20px;
            margin-right: 5px;
            position: relative;
            display: block;
        }

        .navbar-brand:hover,
        .navbar-nav .nav-link:hover {
            text-decoration: none;
        }

        .navbar-nav {
            display: flex;
            align-items: center;
            margin-left: 05px;
        }

        /* Body padding to compensate for fixed navbar */
        body {
            padding-top: 0cm;
            background-color: #ffffff;
            color: #333;
            margin: 0;
        }

        /* Sidebar Styles */
        #sidebar {
            position: fixed;
            top: 2.9cm;
            bottom: 2cm;
            left: 9.5cm;
            width: 180%;
            max-width: 260px;
            max-height: 10%;
            overflow-y: auto;
            box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.0);
            padding: 5px;
            line-height: 20px;
            border-radius: 6px;
            border: 1px solid #ccc;
        }

        #sidebar ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        #sidebar ul li {
            padding: 5px;
            transition: background-color 0.3s;
            cursor: pointer;
        }

        #sidebar ul li:hover {
            background-color: #none;
        }

        #sidebar ul li a {
            color: #000000;
            text-decoration: none;
            font-size: 16px;
            font-family: "Source Sans Pro", Arial, sans-serif;
        }

        #sidebar ul li a i {
            font-size: 10px;
        }

        /* Main Content Styles */
        .container {
            margin-left: 1.5cm;
        }

        /* Sections Styles */
        .data-section {
            margin-bottom: 20px;
        }

        /* Adjusting margin for Introduction */
        .navbar-nav .nav-item:first-child {
            margin-top: 20px;
        }

        /* Active link styles */
        .active-link {
            background-color: #2780e3 !important;
        }

        .active-link a {
            color: white !important;
        }

        /* Code container styles */
        .code-container {
            position: relative;
            background-color: #f8f9fa;
            border: 1px solid #ccc;
            padding: 10px;
            margin-top: 10px;
            border-radius: 6px;
            overflow: hidden;
        }

        pre {
            margin: 0;
            padding: 0;
            overflow-x: auto;
        }

        button {
            position: absolute;
            top: 5px;
            right: 5px;
            background-color: transparent;
            border: none;
            color: #007bff;
            cursor: pointer;
        }

        button:hover {
            color: #0056b3;
        }

        button.copied {
            color: #28a745;
        }

        button.copied:hover {
            color: #218838;
        }
    

    </style>
</head>

<body>
        <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">KODAMA</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="https://moussakassim.github.io/KODAMA1/">Introduction</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#software-tutorial">Software Tutorial</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#simulation">Simulation</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                            data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            Data Analyses
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item"
                                href="https://moussakassim.github.io/Metabolomic-data/">Metabolomic
                                data</a>
                            <a class="dropdown-item"
                                href="https://moussakassim.github.io/Single-cell-Data/">Single
                                cell RNA seq data</a>
                            <a class="dropdown-item"
                                href="https://moussakassim.github.io/Spatial-Transcriptomics/">Spatial
                                Transcriptomic data</a>
                        </div>
                    </li>
                </ul>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="https://github.com/tkcaccia/KODAMA">
                            <span class="fab fa-github"></span>
                            Source code
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
   
    <!-- Sidebar -->
    <div id="sidebar">
        <ul>
            <li id="introLink" data-toggle="tooltip" data-placement="right" title="Single-cell data">
                <a href="#Single-cell data">
                    <i class="fas fa-book-open"></i>
                    <span>Single-cell data</span>
                </a>
            </li>
            <li id="kodamaLink" data-toggle="tooltip" data-placement="right" title="Installation">
                <a href="#Installation">
                    <i class="fas fa-book-open"></i>
                    <span>Installation</span>
                </a>
            </li>
        </ul>
    </div>
     <script>
        // Fonction pour changer le style de l'élément actif
        function setActiveLink(linkId) {
            // Supprimer la classe active-link de tous les éléments
            var links = document.querySelectorAll('#sidebar ul li');
            links.forEach(function (item) {
                item.classList.remove('active-link');
            });

            // Ajouter la classe active-link à l'élément sélectionné
            var selectedLink = document.getElementById(linkId);
            selectedLink.classList.add('active-link');
        }

        // Ajouter un écouteur d'événement pour chaque élément de la barre latérale
        var sidebarLinks = document.querySelectorAll('#sidebar ul li');
        sidebarLinks.forEach(function (link) {
            link.addEventListener('click', function (event) {
                // Empêcher le comportement par défaut du lien
                event.preventDefault();
                
                // Récupérer l'ID de l'élément cliqué
                var linkId = event.currentTarget.id;
                
                // Appeler la fonction pour définir l'élément actif
                setActiveLink(linkId);
            });
        });
    </script>
       <!-- Main Content -->
    <div>
    <!-- Single-cell data Section -->
        <section id="Single-cell data" class="data-section">
            <div class="container">
    <h2>Single-cell data</h2>
    <p>The data set from Tasic et al. encompasses 23,822 cells from adult mouse cortex, split by the authors into 133 clusters with strong hierarchical organisation. A standard preprocessing pipeline consisting of sequencing depth normalisation, feature selection, log-transformation, and reducing the dimensionality to 50 PCs was applied as described by Kobak & Berens in <a href="https://www.nature.com/articles/s41467-019-13056-x" target="_blank">The art of using t-SNE for single-cell transcriptomics</a>.</p>
 </div>
<!-- Tutorial data Section -->
        <section id="Tutorial" class="data-section">
            <div class="container">
    <h2>Tutorial</h2>
    <p>Download the data from <a href="http://celltypes.brain-map.org/rnaseq" target="_blank">here</a> and unpack. Direct links: <a href="http://celltypes.brain-map.org/api/v2/well_known_file_download/694413985" target="_blank">VISp</a>, <a href="http://celltypes.brain-map.org/api/v2/well_known_file_download/694413179" target="_blank">ALM</a>. To get the information about cluster colors and labels (sample_heatmap_plot_data.csv), open the interactive <a href="http://celltypes.brain-map.org/rnaseq/mouse/v1-alm" target="_blank">data browser</a>, go to "Sample Heatmaps", click "Build Plot!" and then "Download data as CSV".</p>

    <div class="code-container">
        <pre>
ta=read.csv("tasic-sample_heatmap_plot_data.txt")
rownames(ta)=ta[,1]
VIS=read.csv("mouse_VISp_gene_expression_matrices_2018-06-14/mouse_VISp_2018-06-14_exon-matrix.csv")
ALM=read.csv("mouse_ALM_gene_expression_matrices_2018-06-14/mouse_ALM_2018-06-14_exon-matrix.csv")
        </pre>
        <button class="copy-btn" onclick="copyCode(this)">Copy</button>
    </div>

    <p>The intron and exon data are merged and the zeros columns are removed.</p>

    <div class="code-container">
        <pre>
data=t(cbind(ALM,VIS))
colnames(data)=as.character(data[1,])
data=data[-1,]
ii=intersect(rownames(data),rownames(ta))
data=data[ii,]
data=data[,colSums(data)!=0]
near.zero.counts=colMeans(data<32)
        </pre>
        <button class="copy-btn" onclick="copyCode(this)">Copy</button>
    </div>

    <p>The data are normalized and the converted to log ratios.</p>

    <div class="code-container">
        <pre>
temp=data
temp[temp<=32]=NA
temp=log2(temp)
m=colMeans(temp,na.rm = TRUE)
y=exp(-1.5*(m-6.56))+0.02
data=data[,which(near.zero.counts>y)]
su=rowSums(data)
data=((data/su)*10^6)*median(su)
data=log2(data+1)
        </pre>
        <button class="copy-btn" onclick="copyCode(this)">Copy</button>
    </div>

    <p>The first 50 principal components are calculated.</p>

    <div class="code-container">
        <pre>
pca=prcomp(data)$x[,1:50]
        </pre>
        <button class="copy-btn" onclick="copyCode(this)">Copy</button>
    </div>

    <p>The KODAMA algorithm is then applied to the 50 PCA and t-SNE is used to visualize the KODAMA dissimilarity matrix.</p>

    <div class="code-container">
        <pre>
kk=KODAMA.matrix(pca)
res_KODAMA_tSNE <- KODAMA.visualization(kk)
plot(res_KODAMA_tSNE,pch=21,bg=ta[,"cluster_color"],main="KODAMA", xlab= "First dimension", ylab = "Second dimension")
        </pre>
        <button class="copy-btn" onclick="copyCode(this)">Copy</button>
    </div>

    <p>The KODAMA clustering are then visualized</p>

    <p align="center">
        <img src="https://gist.github.com/assets/168087487/ecb08dea-0c8d-4822-83fc-8cb406ff9a4c" alt="KODAMA Visualization" height="500" width="500" />
    </p>
    <!-- Bootstrap Scripts -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <!-- Font Awesome Script -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/js/all.min.js"></script>

    <script>
        $(document).ready(function () {
            $('.copy-btn').on('click', function () {
                var $temp = $("<input>");
                $("body").append($temp);
                $temp.val($(this).siblings('pre').text()).select();
                document.execCommand("copy");
                $temp.remove();

                // Change the button appearance when copied
                $(this).addClass('copied');
                setTimeout(() => {
                    $(this).removeClass('copied');
                }, 2000);
            });

            // Highlight active section in the sidebar
            $('body').scrollspy({ target: '#sidebar', offset: 100 });

            // Smooth scrolling for sidebar links
            $('#sidebar ul li a').on('click', function (event) {
                if (this.hash !== "") {
                    event.preventDefault();
                    var hash = this.hash;
                    $('html, body').animate({
                        scrollTop: $(hash).offset().top
                    }, 800, function () {
                        window.location.hash = hash;
                    });
                }
            });
        });
    </script>
</body>

</html>
