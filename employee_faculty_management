-- phpMyAdmin SQL Dump
-- version 4.3.11
-- http://www.phpmyadmin.net
--
-- Host: 127.0.0.1
-- Generation Time: Dec 14, 2015 at 05:58 AM
-- Server version: 5.6.24
-- PHP Version: 5.6.8

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8 */;

--
-- Database: `employee_faculty_management`
--

-- --------------------------------------------------------

--
-- Table structure for table `company_position`
--

CREATE TABLE IF NOT EXISTS `company_position` (
  `id` int(11) NOT NULL,
  `company_position_title` varchar(45) NOT NULL,
  `company_position_date_from` date NOT NULL,
  `company_position_date_to` date NOT NULL,
  `company_position_department` varchar(45) NOT NULL,
  `company_position_salary` varchar(25) NOT NULL,
  `company_position_stepincrement` varchar(25) NOT NULL,
  `company_position_status` varchar(45) NOT NULL,
  `company_position_govt_status` varchar(5) NOT NULL,
  `company_position_faculty_id` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=ucs2;

-- --------------------------------------------------------

--
-- Table structure for table `education`
--

CREATE TABLE IF NOT EXISTS `education` (
  `id` int(11) NOT NULL,
  `education_level` varchar(25) NOT NULL,
  `education_name` varchar(45) NOT NULL,
  `education_degree` varchar(45) NOT NULL,
  `education_year_graduated` varchar(5) NOT NULL,
  `education_hieghest` varchar(10) NOT NULL,
  `education_date_from` date NOT NULL,
  `education_date_to` date NOT NULL,
  `education_scholarship` varchar(25) NOT NULL,
  `education_awards` varchar(45) NOT NULL,
  `education_faculty_id` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=ucs2;

-- --------------------------------------------------------

--
-- Table structure for table `examination`
--

CREATE TABLE IF NOT EXISTS `examination` (
  `id` int(11) NOT NULL,
  `examination_name` varchar(30) NOT NULL,
  `examination_rating` varchar(10) NOT NULL,
  `examination_date` date NOT NULL,
  `examination_place` varchar(30) NOT NULL,
  `examination_licenseNo` varchar(25) NOT NULL,
  `examination_date_of_release` date NOT NULL,
  `examination_faculty_id` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=ucs2;

-- --------------------------------------------------------

--
-- Table structure for table `faculty`
--

CREATE TABLE IF NOT EXISTS `faculty` (
  `id` int(11) NOT NULL,
  `faculty_Iname` varchar(30) NOT NULL,
  `faculty_frame` varchar(30) NOT NULL,
  `faculty_mname` varchar(30) NOT NULL,
  `faculty_name_extention` varchar(7) NOT NULL,
  `faculty_address` varchar(70) NOT NULL,
  `faculty_age` varchar(3) NOT NULL,
  `faculty_sex` varchar(6) NOT NULL,
  `faculty_nationality` varchar(30) NOT NULL,
  `faculty_date_of_birth` date NOT NULL,
  `faculty_civil_status` varchar(20) NOT NULL,
  `faculty_height` varchar(5) NOT NULL,
  `faculty_weight` varchar(5) NOT NULL,
  `faculty_bloddy_type` varchar(5) NOT NULL,
  `faculty_gsis_no` varchar(45) NOT NULL,
  `faculty_pagibig_no` varchar(45) NOT NULL,
  `faculty_phihealt_no` varchar(45) NOT NULL,
  `faculty_sss_no` varchar(45) NOT NULL,
  `faculty_tin_no` varchar(45) NOT NULL,
  `faculty_res_add` varchar(70) NOT NULL,
  `faculty_res_zip` varchar(10) NOT NULL,
  `faculty_res_tel` varchar(15) NOT NULL,
  `faculty_per_add` varchar(70) NOT NULL,
  `faculty_per_zip` varchar(10) NOT NULL,
  `faculty_per_tell` varchar(10) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=ucs2;

-- --------------------------------------------------------

--
-- Table structure for table `organization`
--

CREATE TABLE IF NOT EXISTS `organization` (
  `id` int(11) NOT NULL,
  `organization_name` varchar(45) NOT NULL,
  `organization_address` varchar(45) NOT NULL,
  `organization_date_from` date NOT NULL,
  `organization_date_to` date NOT NULL,
  `organization_hours` varchar(2) NOT NULL,
  `organization_position` varchar(45) NOT NULL,
  `organization_faculty_id` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=ucs2;

-- --------------------------------------------------------

--
-- Table structure for table `post`
--

CREATE TABLE IF NOT EXISTS `post` (
  `id` int(11) NOT NULL,
  `post_title` varchar(45) NOT NULL,
  `post_post` text NOT NULL,
  `post_timecreated` datetime NOT NULL,
  `post_faculty_id` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=ucs2;

-- --------------------------------------------------------

--
-- Table structure for table `postition`
--

CREATE TABLE IF NOT EXISTS `postition` (
  `id` int(11) NOT NULL,
  `postition_position` varchar(25) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=ucs2;

-- --------------------------------------------------------

--
-- Table structure for table `reference`
--

CREATE TABLE IF NOT EXISTS `reference` (
  `id` int(11) NOT NULL,
  `reference_name` varchar(45) NOT NULL,
  `reference_address` varchar(45) NOT NULL,
  `reference_number` varchar(15) NOT NULL,
  `reference_faculty_id` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=ucs2;

-- --------------------------------------------------------

--
-- Table structure for table `user`
--

CREATE TABLE IF NOT EXISTS `user` (
  `id` int(11) NOT NULL,
  `user_username` varchar(25) NOT NULL,
  `user_password` varchar(36) NOT NULL,
  `user_faculty_id` int(11) NOT NULL,
  `user_status` varchar(20) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=ucs2;

--
-- Indexes for dumped tables
--

--
-- Indexes for table `company_position`
--
ALTER TABLE `company_position`
  ADD PRIMARY KEY (`id`);

--
-- Indexes for table `education`
--
ALTER TABLE `education`
  ADD PRIMARY KEY (`id`);

--
-- Indexes for table `examination`
--
ALTER TABLE `examination`
  ADD PRIMARY KEY (`id`);

--
-- Indexes for table `faculty`
--
ALTER TABLE `faculty`
  ADD PRIMARY KEY (`id`);

--
-- Indexes for table `organization`
--
ALTER TABLE `organization`
  ADD PRIMARY KEY (`id`);

--
-- Indexes for table `post`
--
ALTER TABLE `post`
  ADD PRIMARY KEY (`id`);

--
-- Indexes for table `postition`
--
ALTER TABLE `postition`
  ADD PRIMARY KEY (`id`);

--
-- Indexes for table `reference`
--
ALTER TABLE `reference`
  ADD PRIMARY KEY (`id`);

--
-- Indexes for table `user`
--
ALTER TABLE `user`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT for dumped tables
--

--
-- AUTO_INCREMENT for table `company_position`
--
ALTER TABLE `company_position`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `education`
--
ALTER TABLE `education`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `examination`
--
ALTER TABLE `examination`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `faculty`
--
ALTER TABLE `faculty`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `organization`
--
ALTER TABLE `organization`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `post`
--
ALTER TABLE `post`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `postition`
--
ALTER TABLE `postition`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `reference`
--
ALTER TABLE `reference`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `user`
--
ALTER TABLE `user`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
