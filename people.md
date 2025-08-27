---
layout: page
title: People
---

<style>
.people-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

.section-header {
    text-align: center;
    margin: 40px 0 30px 0;
    position: relative;
}

.section-header h2 {
    font-size: 3rem;
    font-weight: 700;
    color: #2c3e50;
    margin-bottom: 10px;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
}

.section-header::after {
    content: '';
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
    width: 80px;
    height: 4px;
    background: linear-gradient(90deg, #3498db, #e74c3c, #f39c12);
    border-radius: 2px;
}

.collaborators-section {
    background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
    border-radius: 20px;
    padding: 40px;
    margin-bottom: 40px;
    box-shadow: 0 15px 35px rgba(0,0,0,0.1);
    border: 1px solid #e9ecef;
}

.mentorships-section {
    background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
    border-radius: 20px;
    padding: 40px;
    margin-bottom: 30px;
    box-shadow: 0 15px 35px rgba(0,0,0,0.1);
    border: 1px solid #dee2e6;
}

.collaborators-content {
    font-size: 1.4rem;
    line-height: 1.8;
    color: #2c3e50;
}

.collaborators-content h3 {
    font-size: 1.8rem;
    font-weight: 600;
    color: #34495e;
    margin-bottom: 20px;
    border-bottom: 2px solid #3498db;
    padding-bottom: 10px;
}

.collaborators-content ul {
    list-style: none;
    padding: 0;
}

.collaborators-content li {
    margin-bottom: 15px;
    padding: 15px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
    border-left: 4px solid #3498db;
    transition: all 0.3s ease;
}

.collaborators-content li:hover {
    transform: translateX(5px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.12);
}

.collaborators-content a {
    color: #2c3e50;
    text-decoration: none;
    font-weight: 600;
}

.collaborators-content a:hover {
    color: #3498db;
}

.mentorships-content {
    font-size: 1.4rem;
    line-height: 1.8;
    color: #2c3e50;
}

.mentorships-content h3 {
    font-size: 1.8rem;
    font-weight: 600;
    color: #34495e;
    margin-bottom: 20px;
    border-bottom: 2px solid #e74c3c;
    padding-bottom: 10px;
}

.mentorships-content h4 {
    font-size: 1.6rem;
    font-weight: 600;
    color: #2c3e50;
    margin: 25px 0 15px 0;
}

.mentorships-content h5 {
    font-size: 1.4rem;
    font-weight: 600;
    color: #34495e;
    margin: 20px 0 10px 0;
    border-bottom: 1px solid #bdc3c7;
    padding-bottom: 5px;
}

.mentorships-content ul {
    list-style: none;
    padding: 0;
}

.mentorships-content li {
    margin-bottom: 15px;
    padding: 15px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
    border-left: 4px solid #e74c3c;
    transition: all 0.3s ease;
}

.mentorships-content li:hover {
    transform: translateX(5px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.12);
}

.mentorships-content a {
    color: #2c3e50;
    text-decoration: none;
    font-weight: 600;
}

.mentorships-content a:hover {
    color: #e74c3c;
}

@media (max-width: 768px) {
    .section-header h2 {
        font-size: 2.5rem;
    }
    
    .collaborators-content,
    .mentorships-content {
        font-size: 1.2rem;
    }
    
    .collaborators-content h3,
    .mentorships-content h3 {
        font-size: 1.6rem;
    }
    
    .mentorships-content h4 {
        font-size: 1.4rem;
    }
}
</style>

<div class="people-container">
    <div class="section-header">
        <h2>Collaborators</h2>
    </div>
    
    <div class="collaborators-section">
        <div class="collaborators-content">
            <h3>Research Collaborators</h3>
            <ul>
                <li><a href="https://www.yu.edu/katz/faculty#:~:text=Liyang%20Yan%27s%20Bio-,Shucheng%20Yu,-AI" target="_blank">Prof. Shucheng Yu</a> - Associate Professor, Yeshiva University</li>
                <li><a href="https://www.stevens.edu/profile/msong6" target="_blank">Prof. Min Song</a> - Professor, Stevens Institute of Technology</li>
                <li><a href="https://faculty.erau.edu/Laxima.NiureKandel" target="_blank">Prof. Laxima Niure Kandel</a> - Assistant Professor, Embry-Riddle Aeronautical University</li>
                <li><a href="https://scholar.google.com/citations?user=v9zFuDEAAAAJ&hl=en" target="_blank">Prof. Yulong Zou</a> - Professor, Nanjing University of Posts and Telecommunications</li>
                <li><a href="https://www.stevens.edu/profile/hli" target="_blank">Prof. Hongbin Li</a> - Professor, Stevens Institute of Technology</li>
                <li><a href="https://www.stevens.edu/profile/ksubbala" target="_blank">Prof. K.P. (Suba) Subbalakshmi</a> - Professor, Stevens Institute of Technology</li>
                <li><a href="https://www.stevens.edu/profile/ywang6" target="_blank">Prof. Ying Wang</a> - Associate Professor, Stevens Institute of Technology</li>
                <li><a href="https://www2.hawaii.edu/~yaozheng/" target="_blank">Prof. Yao Zheng</a> - Associate Professor, University of Hawaii at Mānoa</li>
                <li>Prof. Moh Khalid Hasan - Assistant Professor, James Madison University</li>
            </ul>
        </div>
    </div>
    
    <div class="section-header">
        <h2>Mentorships</h2>
    </div>
    
    <div class="mentorships-section">
        <div class="mentorships-content">
            <h3>Current Projects</h3>
             <h4>Group Mentorship</h4>
             <ul>
                 <li><a href="https://wbi-innovates.zohobackstage.com/afrlsdr" target="_blank">AFRL Software Design Radio (SDR) Challenge 2024-2025</a></li>
             </ul>
             
             <h5>Undergraduate Members</h5>
             <ul>
                 <li>Shaun George</li>
                 <li>Lenny Yanza</li>
                 <li>Karen Caguana</li>
                 <li>Xiangxi (Mall) Wang</li>
             </ul>
             
             <h5>High School Member</h5>
             <ul>
                 <li>Akshat Santhana Gopalan</li>
             </ul>
            
            <h4>Individual Mentorship</h4>
            <ul>
                <li><a href="https://srparkar.github.io/" target="_blank">Saurabh Raman Parkar</a> - Master, AI Integrated Sensing</li>
                <li>Ruoxi Li - Master, AI Integrated Sensing</li>
                <li>Beula Jose - Master, Wireless Security</li>
                <li>Zhifan Jiang - Master, SDR</li>
                <li>Jiapeng Xiao - Master, SDR</li>
            </ul>
        </div>
    </div>
</div>